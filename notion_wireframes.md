graph TD;
    subgraph Notion_Workspace
        style Notion_Workspace fill:#f9f,stroke:#333,stroke-width:4px;
        subgraph Sidebar_Navigation
            style Sidebar_Navigation fill:#eee,stroke:#333,stroke-width:2px,stroke-dasharray: 5, 5;
            Dashboard
            Tasks
            Projects
            Notes
            Calendar
            Templates
        end
        Dashboard
        Tasks
        Projects
        Notes
        Calendar
        Templates
    end
    Dashboard --> |Welcome Message| Dashboard_Content
    Dashboard --> |Quick Links| Tasks, Projects, Notes
    Dashboard --> |Upcoming Events| Calendar
    Tasks --> |Task 1| Task_Details
    Tasks --> |Task 2| Task_Details
    Tasks --> |Task 3| Task_Details
    Tasks --> |Add Task Button| Add_Task
    Projects --> |Project 1| Project_Details
    Projects --> |Project 2| Project_Details
    Projects --> |Project 3| Project_Details
    Projects --> |Add Project Button| Add_Project
    Notes --> |Note 1| Note_Details
    Notes --> |Note 2| Note_Details
    Notes --> |Note 3| Note_Details
    Notes --> |Add Note Button| Add_Note
    Calendar --> |Month View| Calendar_Month
    Calendar --> |Week View| Calendar_Week
    Calendar --> |Day View| Calendar_Day
    Templates --> |Template 1| Template_Details
    Templates --> |Template 2| Template_Details
    Templates --> |Template 3| Template_Details
    Templates --> |Create New Template Button| Create_Template
