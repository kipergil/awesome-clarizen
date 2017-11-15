{
  "entityDescriptions": [
    {
      "typeName": "Note",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Note",
      "labelPlural": "Notes",
      "parentEntity": "Comment",
      "displayField": "Name",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "Post",
      "fields": null,
      "validStates": [
        
      ],
      "label": "V5 Post",
      "labelPlural": "V5 Posts",
      "parentEntity": "Comment",
      "displayField": "Name",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "Email",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Email",
      "labelPlural": "Emails",
      "parentEntity": "Comment",
      "displayField": "Subject",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "Comment",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Collaboration Items",
      "labelPlural": "",
      "parentEntity": null,
      "displayField": "Name",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "Template",
      "fields": null,
      "validStates": [
        "Being Modified",
        "Published"
      ],
      "label": "Template",
      "labelPlural": "Templates",
      "parentEntity": null,
      "displayField": "Name",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "NonLaborResource",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Non-Labor Resource",
      "labelPlural": "Non-Labor Resources",
      "parentEntity": "GenericResourceEntity",
      "displayField": "Name",
      "disabled": true,
      "relations": null
    },
    {
      "typeName": "User",
      "fields": null,
      "validStates": [
        "Active",
        "Deleted",
        "Disabled",
        "Pending"
      ],
      "label": "User",
      "labelPlural": "People",
      "parentEntity": "ResourceEntity",
      "displayField": "DisplayName",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "Profile",
      "fields": null,
      "validStates": [
        "Active",
        "Inactive"
      ],
      "label": "Profile",
      "labelPlural": "Profile",
      "parentEntity": "ResourceEntity",
      "displayField": "Name",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "DiscussionGroup",
      "fields": null,
      "validStates": [
        "Active",
        "Inactive"
      ],
      "label": "Discussion Group",
      "labelPlural": "Discussion Groups",
      "parentEntity": "Group",
      "displayField": "Name",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "UserGroup",
      "fields": null,
      "validStates": [
        "Active",
        "Inactive"
      ],
      "label": "User Group",
      "labelPlural": "User Groups",
      "parentEntity": "Group",
      "displayField": "Name",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "Group",
      "fields": null,
      "validStates": [
        "Active",
        "Inactive"
      ],
      "label": "Group",
      "labelPlural": "Groups",
      "parentEntity": "ResourceGroupEntity",
      "displayField": "Name",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "Skill",
      "fields": null,
      "validStates": [
        "Active",
        "Inactive"
      ],
      "label": "Skill",
      "labelPlural": "Skills",
      "parentEntity": "ResourceGroupEntity",
      "displayField": "Name",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "JobTitle",
      "fields": null,
      "validStates": [
        "Active",
        "Inactive"
      ],
      "label": "Job Title",
      "labelPlural": "Job Titles",
      "parentEntity": "ResourceGroupEntity",
      "displayField": "Name",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "ResourceGroupEntity",
      "fields": null,
      "validStates": [
        "Active",
        "Inactive"
      ],
      "label": "Group",
      "labelPlural": "Groups",
      "parentEntity": "ResourceEntity",
      "displayField": "Name",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "ResourceEntity",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Groups And Users",
      "labelPlural": "Groups Or Users",
      "parentEntity": "GenericResourceEntity",
      "displayField": "Name",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "GenericResourceEntity",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Users And Resources",
      "labelPlural": "Generic Resource Entity",
      "parentEntity": null,
      "displayField": "Name",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "FileTemplate",
      "fields": null,
      "validStates": [
        
      ],
      "label": "File Template",
      "labelPlural": "File Templates",
      "parentEntity": "BaseFile",
      "displayField": "Name",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "Document",
      "fields": null,
      "validStates": [
        
      ],
      "label": "File",
      "labelPlural": "Files",
      "parentEntity": "BaseFile",
      "displayField": "Name",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "BaseFile",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Files",
      "labelPlural": "base Files",
      "parentEntity": null,
      "displayField": "Name",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "LaborResourceLinkAggregated",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Labor Resource link aggregated",
      "labelPlural": "",
      "parentEntity": "LaborResourceLink",
      "displayField": "WorkItem",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "LaborResourceLinkDirect",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Labor Resource link direct",
      "labelPlural": "",
      "parentEntity": "LaborResourceLink",
      "displayField": "WorkItem",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "LaborResourceLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Labor resource link",
      "labelPlural": "Labor resource links",
      "parentEntity": "ResourceLinkFinancial",
      "displayField": "WorkItem",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "NonLaborResourceLinkAggregated",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Non-Labor Resource link aggregated",
      "labelPlural": "",
      "parentEntity": "NonLaborResourceLink",
      "displayField": null,
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "NonLaborResourceLinkDirect",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Non-Labor Resource link direct",
      "labelPlural": "",
      "parentEntity": "NonLaborResourceLink",
      "displayField": "WorkItem",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "NonLaborResourceLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Non-Labor Resource link",
      "labelPlural": "Non-Labor Resource links",
      "parentEntity": "ResourceLinkFinancial",
      "displayField": "WorkItem",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "ResourceLinkFinancial",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Financial Resource Link",
      "labelPlural": "Resource links",
      "parentEntity": null,
      "displayField": "WorkItem",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "LaborResourceTimePhase",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Labor time phase data",
      "labelPlural": "",
      "parentEntity": "ResourceTimePhase",
      "displayField": "ExternalID",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "NonLaborResourceTimePhase",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Non-Labor time phase data",
      "labelPlural": "",
      "parentEntity": "ResourceTimePhase",
      "displayField": "ExternalID",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "ResourceTimePhase",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Financial Resource time phase",
      "labelPlural": "",
      "parentEntity": null,
      "displayField": "ExternalID",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "LaborResourceSnapshot",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Labor resource snapshot",
      "labelPlural": "",
      "parentEntity": null,
      "displayField": "Name",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "AdditionalObjectProperties",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Additional Object Properties",
      "labelPlural": "",
      "parentEntity": null,
      "displayField": "Overview",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "PushNotification",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Push Notification",
      "labelPlural": "",
      "parentEntity": null,
      "displayField": "ExternalID",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "Data",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Data",
      "labelPlural": "",
      "parentEntity": null,
      "displayField": "Name",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "WorkByDay",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Task Assignment",
      "labelPlural": "",
      "parentEntity": "ResourceCalendarException",
      "displayField": "ExternalID",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "ResourceCalendarExceptionAbsolute",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Project Assignment",
      "labelPlural": "",
      "parentEntity": "ResourceCalendarException",
      "displayField": "ExternalID",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "ResourceCalendarExceptionRelative",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Resource Calendar Exception Relative",
      "labelPlural": "",
      "parentEntity": "ResourceCalendarException",
      "displayField": "ExternalID",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "ResourceCalendarException",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Resource Calendar Exception",
      "labelPlural": "",
      "parentEntity": null,
      "displayField": "ExternalID",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "ReportShortcutLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Report Shortcut",
      "labelPlural": "",
      "parentEntity": "ReportsFolderContentLink",
      "displayField": "Parent",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "ReportsHierarchyLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Reports Hierarchy",
      "labelPlural": "",
      "parentEntity": "ReportsFolderContentLink",
      "displayField": "Parent",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "ReportsFolderContentLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Reports Folder Content",
      "labelPlural": "",
      "parentEntity": "FolderContentLink",
      "displayField": "Parent",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "FolderContentLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Folder Content",
      "labelPlural": "",
      "parentEntity": null,
      "displayField": "Parent",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "Dashboard",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Dashboard",
      "labelPlural": "Dashboards",
      "parentEntity": "ReportAndDashboard",
      "displayField": "Name",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "Report",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Report",
      "labelPlural": "Reports",
      "parentEntity": "ReportAndDashboard",
      "displayField": "Name",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "ReportAndDashboard",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Reports And Dashboards",
      "labelPlural": "Reports",
      "parentEntity": "FoldersAndReports",
      "displayField": "Name",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "FolderForReport",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Reports Folder",
      "labelPlural": "Folders",
      "parentEntity": "FoldersAndReports",
      "displayField": "Name",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "FoldersAndReports",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Folder and Report",
      "labelPlural": "Folders and Reports",
      "parentEntity": null,
      "displayField": "Name",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "Permission",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Permission Definitions",
      "labelPlural": "",
      "parentEntity": null,
      "displayField": "Entity",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "DependencyLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Dependency",
      "labelPlural": "",
      "parentEntity": null,
      "displayField": "WorkItem",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "IntegrationsRegistry",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Integrations Registry",
      "labelPlural": "",
      "parentEntity": null,
      "displayField": "Name",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "TopicDocumentLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Topic Document Link",
      "labelPlural": "",
      "parentEntity": "TopicLink",
      "displayField": "Topic",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "TopicDiscussionLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Topic Discussion Link",
      "labelPlural": "",
      "parentEntity": "TopicLink",
      "displayField": "Topic",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "TopicGroupLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Topic Group Link",
      "labelPlural": "",
      "parentEntity": "TopicLink",
      "displayField": "Topic",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "TopicExpenseEntryLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Topic ExpenseEntry Link",
      "labelPlural": "",
      "parentEntity": "TopicLink",
      "displayField": "Topic",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "TopicExpenseSheetLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Topic ExpenseSheet Link",
      "labelPlural": "",
      "parentEntity": "TopicLink",
      "displayField": "Topic",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "TopicCustomerLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Topic Customer Link",
      "labelPlural": "",
      "parentEntity": "TopicLink",
      "displayField": "Topic",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "TopicCaseLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Topic Case Link",
      "labelPlural": "",
      "parentEntity": "TopicLink",
      "displayField": "Topic",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "TopicWorkItemLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Topic WorkItem Link",
      "labelPlural": "",
      "parentEntity": "TopicLink",
      "displayField": "Topic",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "TopicLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Topic Link",
      "labelPlural": "",
      "parentEntity": null,
      "displayField": "Topic",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "Milestone",
      "fields": null,
      "validStates": [
        "Requested",
        "Draft",
        "Active",
        "On Hold",
        "Cancelled",
        "Completed"
      ],
      "label": "Milestone",
      "labelPlural": "Milestones",
      "parentEntity": "PlanningComponent",
      "displayField": "Name",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "Task",
      "fields": null,
      "validStates": [
        "Requested",
        "Draft",
        "Active",
        "On Hold",
        "Cancelled",
        "Completed"
      ],
      "label": "Task",
      "labelPlural": "Tasks",
      "parentEntity": "GenericTask",
      "displayField": "Name",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "RecurringTask",
      "fields": null,
      "validStates": [
        "Requested",
        "Draft",
        "Active",
        "On Hold",
        "Cancelled",
        "Completed"
      ],
      "label": "Recurring Task",
      "labelPlural": "Recurring Tasks",
      "parentEntity": "GenericTask",
      "displayField": "Name",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "GenericTask",
      "fields": null,
      "validStates": [
        "Requested",
        "Draft",
        "Active",
        "On Hold",
        "Cancelled",
        "Completed"
      ],
      "label": "Task",
      "labelPlural": "Tasks",
      "parentEntity": "PlanningComponent",
      "displayField": "Name",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "PlanningComponent",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Planning Component",
      "labelPlural": "",
      "parentEntity": "WorkItem",
      "displayField": "Name",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "Project",
      "fields": null,
      "validStates": [
        "Requested",
        "Draft",
        "Active",
        "On Hold",
        "Cancelled",
        "Completed"
      ],
      "label": "Project",
      "labelPlural": "Projects",
      "parentEntity": "GenericProject",
      "displayField": "Name",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "Program",
      "fields": null,
      "validStates": [
        "Requested",
        "Draft",
        "Active",
        "On Hold",
        "Cancelled",
        "Completed"
      ],
      "label": "Program",
      "labelPlural": "Programs",
      "parentEntity": "GenericProject",
      "displayField": "Name",
      "disabled": true,
      "relations": null
    },
    {
      "typeName": "GenericProject",
      "fields": null,
      "validStates": [
        "Requested",
        "Draft",
        "Active",
        "On Hold",
        "Cancelled",
        "Completed"
      ],
      "label": "Project or Program",
      "labelPlural": "Projects or Programs",
      "parentEntity": "WorkItem",
      "displayField": "Name",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "WorkItem",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Work Item",
      "labelPlural": "Work Items",
      "parentEntity": null,
      "displayField": "Name",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "Topic",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Topic",
      "labelPlural": "Topics",
      "parentEntity": null,
      "displayField": "Name",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "Following",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Following",
      "labelPlural": "",
      "parentEntity": null,
      "displayField": "User",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "Like",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Like",
      "labelPlural": "",
      "parentEntity": null,
      "displayField": "User",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "NLRDiscussionLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Non-Labor Resource Discussion Link",
      "labelPlural": "",
      "parentEntity": "DiscussionLink",
      "displayField": "DiscussionMessage",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "ReportDiscussionLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Report Discussion Link",
      "labelPlural": "",
      "parentEntity": "DiscussionLink",
      "displayField": "DiscussionMessage",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "UserReportDiscussionLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Report Discussion Link",
      "labelPlural": "",
      "parentEntity": "DiscussionLink",
      "displayField": "DiscussionMessage",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "SystemReportDiscussionLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Saved Report Discussion Link",
      "labelPlural": "",
      "parentEntity": "DiscussionLink",
      "displayField": "DiscussionMessage",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "ExpenseEntryDiscussionLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "ExpenseEntry Discussion Link",
      "labelPlural": "",
      "parentEntity": "DiscussionLink",
      "displayField": "DiscussionMessage",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "ExpenseSheetDiscussionLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "ExpenseSheet Discussion Link",
      "labelPlural": "",
      "parentEntity": "DiscussionLink",
      "displayField": "DiscussionMessage",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "CustomerDiscussionLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Customer Discussion Link",
      "labelPlural": "",
      "parentEntity": "DiscussionLink",
      "displayField": "DiscussionMessage",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "CaseDiscussionLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Case Discussion Link",
      "labelPlural": "",
      "parentEntity": "DiscussionLink",
      "displayField": "DiscussionMessage",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "WorkItemDiscussionLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "WorkItem Discussion Link",
      "labelPlural": "",
      "parentEntity": "DiscussionLink",
      "displayField": "DiscussionMessage",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "DiscussionLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Discussion Links",
      "labelPlural": "",
      "parentEntity": null,
      "displayField": "DiscussionMessage",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "DiscussionReply",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Reply",
      "labelPlural": "Replies",
      "parentEntity": "DiscussionMessage",
      "displayField": "Text",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "DiscussionPost",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Post",
      "labelPlural": "Posts",
      "parentEntity": "DiscussionMessage",
      "displayField": "Text",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "DiscussionMessage",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Discussion Message",
      "labelPlural": "Discussion Messages",
      "parentEntity": null,
      "displayField": "Text",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "GroupTaskLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Group Task Link",
      "labelPlural": "",
      "parentEntity": "GroupLink",
      "displayField": "Group",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "GroupProjectLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Group Project Link",
      "labelPlural": "",
      "parentEntity": "GroupLink",
      "displayField": "Group",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "GroupCaseLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Group Case Link",
      "labelPlural": "",
      "parentEntity": "GroupLink",
      "displayField": "Group",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "GroupCustomerLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Group Customer Link",
      "labelPlural": "",
      "parentEntity": "GroupLink",
      "displayField": "Group",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "GroupLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Group Link",
      "labelPlural": "",
      "parentEntity": null,
      "displayField": "Group",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "RecycleBinItems",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Recycle Bin Items",
      "labelPlural": "",
      "parentEntity": null,
      "displayField": null,
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "Stopwatch",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Stopwatch",
      "labelPlural": "Stopwatches",
      "parentEntity": null,
      "displayField": "WorkItem",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "ProfileLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Profile Link",
      "labelPlural": "",
      "parentEntity": "MembershipLink",
      "displayField": "Container",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "SubGroupHierarchyLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Group Hierarchy",
      "labelPlural": "",
      "parentEntity": "GroupHierarchyLink",
      "displayField": "Container",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "GroupMembershipLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Group Member",
      "labelPlural": "",
      "parentEntity": "GroupHierarchyLink",
      "displayField": "Container",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "GroupHierarchyLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "User Group Hierarchy",
      "labelPlural": "",
      "parentEntity": "MembershipLink",
      "displayField": "Container",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "SkillLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Skill Link",
      "labelPlural": "",
      "parentEntity": "MembershipLink",
      "displayField": "Container",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "MembershipLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Membership",
      "labelPlural": "",
      "parentEntity": null,
      "displayField": "Container",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "NLRAttachmentLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Attachment",
      "labelPlural": "",
      "parentEntity": "AttachmentLink",
      "displayField": "Entity",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "WorkItemAttachmentLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Attachment",
      "labelPlural": "",
      "parentEntity": "AttachmentLink",
      "displayField": "Entity",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "DashboardAttachmentLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Attachments",
      "labelPlural": "",
      "parentEntity": "AttachmentLink",
      "displayField": "Entity",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "ReportAttachmentLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Attachments",
      "labelPlural": "",
      "parentEntity": "AttachmentLink",
      "displayField": "Entity",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "UserAttachmentLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Attachment",
      "labelPlural": "",
      "parentEntity": "AttachmentLink",
      "displayField": "Entity",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "ExpenseSheetAttachmentLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Attachment",
      "labelPlural": "",
      "parentEntity": "AttachmentLink",
      "displayField": "Entity",
      "disabled": false,
      "relations": null
    },
    {
      "typeName": "CustomerAttachmentLink",
      "fields": null,
      "validStates": [
        
      ],
      "label": "Attachment",
      "labelPlural": "",
      "parentEntity": "AttachmentLink",
      "displayField": "Entity",
      "disabled": false,
      "relations": null
    }
  ]
}
