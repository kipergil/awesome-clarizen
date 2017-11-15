```javascript

{
   "entityRelations": [
      {
         "typeName": "Note",
         "relations": []
      },
      {
         "typeName": "Post",
         "relations": []
      },
      {
         "typeName": "Email",
         "relations": []
      },
      {
         "typeName": "Comment",
         "relations": []
      },
      {
         "typeName": "Template",
         "relations": []
      },
      {
         "typeName": "NonLaborResource",
         "relations": [
            {
               "name": "Discussions",
               "label": "Discussions",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "",
               "relatedTypeName": "DiscussionPost",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Documents",
               "label": "Files",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "NLRAttachmentLink",
               "relatedTypeName": "Document",
               "sourceFieldName": "Entity"
            },
            {
               "name": "NLROfWorkItems",
               "label": "Related Work Items",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "NonLaborResourceLinkAggregated",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "NonLaborResource"
            }
         ]
      },
      {
         "typeName": "User",
         "relations": [
            {
               "name": "TechAccountManagerOfCustomers",
               "label": "Technical Account Manager of Customers",
               "roleLabel": "Customer Technical Account Manager",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Customer",
               "sourceFieldName": "TechnicalAccountManager"
            },
            {
               "name": "AccountOwnerOfCustomers",
               "label": "Account Owner of Customers",
               "roleLabel": "Customer Account Owner",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Customer",
               "sourceFieldName": "Owner"
            },
            {
               "name": "DirectFollowers",
               "label": "Direct Followers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Following",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Followers",
               "label": "Followers",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "UsersImFollowing",
               "label": "Users following",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "CreatedTimesheets",
               "label": "Created Timesheets",
               "roleLabel": "Creator",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Timesheet",
               "sourceFieldName": "CreatedBy"
            },
            {
               "name": "AttachedNotes",
               "label": "Notes",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Note",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "MemberOfWorkItems",
               "label": "Related Work Items",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "WorkItemTeamLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Resource"
            },
            {
               "name": "MemberOfGroups",
               "label": "Groups",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupMembershipLink",
               "relatedTypeName": "Group",
               "sourceFieldName": "Member"
            },
            {
               "name": "ApprovedTimesheets",
               "label": "Approved Timesheets",
               "roleLabel": "Approver",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Timesheet",
               "sourceFieldName": "ApprovedBy"
            },
            {
               "name": "OwnedExpenses",
               "label": "Owner of Expenses",
               "roleLabel": "Owner",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "ExpenseSheet",
               "sourceFieldName": "Owner"
            },
            {
               "name": "ExpensesApprovedBy",
               "label": "Approved Expenses",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "ExpenseSheet",
               "sourceFieldName": "ApprovedBy"
            },
            {
               "name": "ApproverOfExpenses",
               "label": "Approver of Expenses",
               "roleLabel": "Expense Approver",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "ExpenseSheet",
               "sourceFieldName": "Approver"
            },
            {
               "name": "OwnerOfIssues",
               "label": "Owned Cases",
               "roleLabel": "Owner",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "Owner"
            },
            {
               "name": "AssignedIssues",
               "label": "Assigned Cases",
               "roleLabel": "Assigned to",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "AssignedTo"
            },
            {
               "name": "SubmittedIssues",
               "label": "Submitted Cases",
               "roleLabel": "Submitted by",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "SubmittedBy"
            },
            {
               "name": "EvaluatedIssues",
               "label": "Evaluated Cases",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "EvaluatedBy"
            },
            {
               "name": "OpenedByIssues",
               "label": "Opened Cases",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "OpenedBy"
            },
            {
               "name": "ResolvedIssues",
               "label": "Resolved Cases",
               "roleLabel": "Resolved by",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "ResolvedBy"
            },
            {
               "name": "ClosedByIssues",
               "label": "Closed Cases",
               "roleLabel": "Closed by",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "ClosedBy"
            },
            {
               "name": "RejectedIssues",
               "label": "Rejected Cases",
               "roleLabel": "Rejected by",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "RejectedBy"
            },
            {
               "name": "ReopenedIssues",
               "label": "Reopened Cases",
               "roleLabel": "Reopened by",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "ReopenedBy"
            },
            {
               "name": "DeferredByIssues",
               "label": "Deferred Cases",
               "roleLabel": "Deferred by",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "DeferredBy"
            },
            {
               "name": "Issues",
               "label": "Member of Cases",
               "roleLabel": "Team Member",
               "readOnly": true,
               "linkTypeName": "IssueTeamMembers",
               "relatedTypeName": "Case",
               "sourceFieldName": "TeamMember"
            },
            {
               "name": "AssignedWorkItems",
               "label": "Assigned Work Items",
               "roleLabel": "Resource",
               "readOnly": true,
               "linkTypeName": "RegularResourceLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Resource"
            },
            {
               "name": "ReviewerOfWorkItems",
               "label": "Reviewer of Work Items",
               "roleLabel": "Reviewer",
               "readOnly": true,
               "linkTypeName": "ReviewerLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Resource"
            },
            {
               "name": "ManagerOfWorkItems",
               "label": "Managed Work Items",
               "roleLabel": "Manager",
               "readOnly": true,
               "linkTypeName": "ManagerResourceLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Resource"
            },
            {
               "name": "MemberOf",
               "label": "Member of (Obsolete)",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupHierarchyLink",
               "relatedTypeName": "Group",
               "sourceFieldName": "Member"
            },
            {
               "name": "Skills",
               "label": "Skills",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "SkillLink",
               "relatedTypeName": "Skill",
               "sourceFieldName": "Member"
            },
            {
               "name": "ProjectManagerOfProjects",
               "label": "Managed Projects",
               "roleLabel": "Project Manager",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "GenericProject",
               "sourceFieldName": "ProjectManager"
            },
            {
               "name": "ProjectSponsorOfProjects",
               "label": "Sponsored Projects",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "GenericProject",
               "sourceFieldName": "ProjectSponsor"
            },
            {
               "name": "Subordinates",
               "label": "Direct Reports",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": "DirectManager"
            },
            {
               "name": "WorkItems",
               "label": "Related Work Items (Obsolete)",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ResourceLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Resource"
            },
            {
               "name": "WorkItemIOpenedStopwatch",
               "label": "Active Stopwatches",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "Stopwatch",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "User"
            },
            {
               "name": "RecipientOfEmails",
               "label": "Recipient Of Emails",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "EmailRecipient",
               "sourceFieldName": "Recipient"
            },
            {
               "name": "Discussions",
               "label": "Discussions",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "",
               "relatedTypeName": "DiscussionPost",
               "sourceFieldName": "Entity"
            },
            {
               "name": "DirectManagerOfGroups",
               "label": "Manager of Groups",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "UserGroup",
               "sourceFieldName": "DirectManager"
            },
            {
               "name": "ReportedTimesheets",
               "label": "Reported Timesheets",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Timesheet",
               "sourceFieldName": "ReportedBy"
            },
            {
               "name": "OwnedProofs",
               "label": "Owned Proofs",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Document",
               "sourceFieldName": "ProofOwner"
            },
            {
               "name": "Documents",
               "label": "Files",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "UserAttachmentLink",
               "relatedTypeName": "Document",
               "sourceFieldName": "Entity"
            },
            {
               "name": "DataObjects",
               "label": "DataObjects",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "SourceObject"
            },
            {
               "name": "OwnedWorkItem",
               "label": "Owned Work Items",
               "roleLabel": "Owner",
               "readOnly": true,
               "linkTypeName": "OwnerLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Resource"
            },
            {
               "name": "UserOpenProofs",
               "label": "Open Proofs",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Document",
               "sourceFieldName": null
            },
            {
               "name": "ProgramManager",
               "label": "Managed Program Components",
               "roleLabel": "Program Manager Direct",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Program",
               "sourceFieldName": "ProgramManager"
            },
            {
               "name": "R_ResourceCost",
               "label": "Resource Cost",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "C_ResourceCost"
            },
            {
               "name": "R_LeaveEntitlements",
               "label": "Leave Entitlements",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "C_LeaveEntitlementfor"
            },
            {
               "name": "R_CustomerPortfolio",
               "label": "CustomerPortfolio",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Customer",
               "sourceFieldName": "C_CommercialManager"
            },
            {
               "name": "R_ManageAbsenceFor",
               "label": "Manage Absence For",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": "C_AbsenceManager"
            },
            {
               "name": "R_UserRate",
               "label": "User Rate",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "C_UserRate"
            },
            {
               "name": "R_AbsenceRequests",
               "label": "Absence Requests",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "C_AbsenceRequestsfor"
            }
         ]
      },
      {
         "typeName": "Profile",
         "relations": [
            {
               "name": "ProfileUserGroups",
               "label": "Profile Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ProfileLink",
               "relatedTypeName": "ResourceEntity",
               "sourceFieldName": "Container"
            }
         ]
      },
      {
         "typeName": "DiscussionGroup",
         "relations": [
            {
               "name": "LikedBy",
               "label": "Liked By",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Like",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "RecipientOfEmails",
               "label": "Recipient Of Emails",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "EmailRecipient",
               "sourceFieldName": "Recipient"
            },
            {
               "name": "GroupMembers",
               "label": "Group Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupMembershipLink",
               "relatedTypeName": "User",
               "sourceFieldName": "Container"
            },
            {
               "name": "Projects",
               "label": "Projects",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupProjectLink",
               "relatedTypeName": "GenericProject",
               "sourceFieldName": "Group"
            },
            {
               "name": "Tasks",
               "label": "Tasks",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupTaskLink",
               "relatedTypeName": "GenericTask",
               "sourceFieldName": "Group"
            },
            {
               "name": "Customers",
               "label": "Customers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCustomerLink",
               "relatedTypeName": "Customer",
               "sourceFieldName": "Group"
            },
            {
               "name": "Cases",
               "label": "Cases",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCaseLink",
               "relatedTypeName": "Case",
               "sourceFieldName": "Group"
            },
            {
               "name": "Discussions",
               "label": "Discussions",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "",
               "relatedTypeName": "DiscussionPost",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Topics",
               "label": "Topics",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "TopicGroupLink",
               "relatedTypeName": "Topic",
               "sourceFieldName": "Entity"
            },
            {
               "name": "DataObjects",
               "label": "DataObjects",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "SourceObject"
            },
            {
               "name": "IssuesForGroup",
               "label": "Issues",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCaseLink",
               "relatedTypeName": "Issue",
               "sourceFieldName": "Group"
            },
            {
               "name": "RisksForGroup",
               "label": "Risks",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCaseLink",
               "relatedTypeName": "Risk",
               "sourceFieldName": "Group"
            },
            {
               "name": "BugsForGroup",
               "label": "Bugs",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCaseLink",
               "relatedTypeName": "Bug",
               "sourceFieldName": "Group"
            },
            {
               "name": "EnhancementRequestForGroup",
               "label": "Enhancement Requests",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCaseLink",
               "relatedTypeName": "EnhancementRequest",
               "sourceFieldName": "Group"
            },
            {
               "name": "Documents",
               "label": "Files",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ResourceGroupEntityAttachmentLink",
               "relatedTypeName": "Document",
               "sourceFieldName": "Entity"
            }
         ]
      },
      {
         "typeName": "UserGroup",
         "relations": [
            {
               "name": "LikedBy",
               "label": "Liked By",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Like",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "SubGroups",
               "label": "Sub Groups",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "SubGroupHierarchyLink",
               "relatedTypeName": "UserGroup",
               "sourceFieldName": "Container"
            },
            {
               "name": "ParentGroups",
               "label": "Member of",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "SubGroupHierarchyLink",
               "relatedTypeName": "UserGroup",
               "sourceFieldName": "Member"
            },
            {
               "name": "RecipientOfEmails",
               "label": "Recipient Of Emails",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "EmailRecipient",
               "sourceFieldName": "Recipient"
            },
            {
               "name": "Members",
               "label": "Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupHierarchyLink",
               "relatedTypeName": "ResourceEntity",
               "sourceFieldName": "Container"
            },
            {
               "name": "MemberOf",
               "label": "Member of (Obsolete)",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupHierarchyLink",
               "relatedTypeName": "UserGroup",
               "sourceFieldName": "Member"
            },
            {
               "name": "Skills",
               "label": "Skills",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "SkillLink",
               "relatedTypeName": "Skill",
               "sourceFieldName": "Member"
            },
            {
               "name": "AllMembers",
               "label": "All Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "GroupMembers",
               "label": "Group Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupMembershipLink",
               "relatedTypeName": "User",
               "sourceFieldName": "Container"
            },
            {
               "name": "Projects",
               "label": "Projects",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupProjectLink",
               "relatedTypeName": "GenericProject",
               "sourceFieldName": "Group"
            },
            {
               "name": "Tasks",
               "label": "Tasks",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupTaskLink",
               "relatedTypeName": "GenericTask",
               "sourceFieldName": "Group"
            },
            {
               "name": "Customers",
               "label": "Customers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCustomerLink",
               "relatedTypeName": "Customer",
               "sourceFieldName": "Group"
            },
            {
               "name": "Cases",
               "label": "Cases",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCaseLink",
               "relatedTypeName": "Case",
               "sourceFieldName": "Group"
            },
            {
               "name": "Discussions",
               "label": "Discussions",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "",
               "relatedTypeName": "DiscussionPost",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Topics",
               "label": "Topics",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "TopicGroupLink",
               "relatedTypeName": "Topic",
               "sourceFieldName": "Entity"
            },
            {
               "name": "DataObjects",
               "label": "DataObjects",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "SourceObject"
            },
            {
               "name": "IssuesForGroup",
               "label": "Issues",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCaseLink",
               "relatedTypeName": "Issue",
               "sourceFieldName": "Group"
            },
            {
               "name": "RisksForGroup",
               "label": "Risks",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCaseLink",
               "relatedTypeName": "Risk",
               "sourceFieldName": "Group"
            },
            {
               "name": "BugsForGroup",
               "label": "Bugs",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCaseLink",
               "relatedTypeName": "Bug",
               "sourceFieldName": "Group"
            },
            {
               "name": "EnhancementRequestForGroup",
               "label": "Enhancement Requests",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCaseLink",
               "relatedTypeName": "EnhancementRequest",
               "sourceFieldName": "Group"
            },
            {
               "name": "Documents",
               "label": "Files",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ResourceGroupEntityAttachmentLink",
               "relatedTypeName": "Document",
               "sourceFieldName": "Entity"
            }
         ]
      },
      {
         "typeName": "Group",
         "relations": [
            {
               "name": "GroupMembers",
               "label": "Group Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupMembershipLink",
               "relatedTypeName": "User",
               "sourceFieldName": "Container"
            },
            {
               "name": "Projects",
               "label": "Projects",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupProjectLink",
               "relatedTypeName": "GenericProject",
               "sourceFieldName": "Group"
            },
            {
               "name": "Tasks",
               "label": "Tasks",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupTaskLink",
               "relatedTypeName": "GenericTask",
               "sourceFieldName": "Group"
            },
            {
               "name": "Customers",
               "label": "Customers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCustomerLink",
               "relatedTypeName": "Customer",
               "sourceFieldName": "Group"
            },
            {
               "name": "Cases",
               "label": "Cases",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCaseLink",
               "relatedTypeName": "Case",
               "sourceFieldName": "Group"
            },
            {
               "name": "Discussions",
               "label": "Discussions",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "",
               "relatedTypeName": "DiscussionPost",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Topics",
               "label": "Topics",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "TopicGroupLink",
               "relatedTypeName": "Topic",
               "sourceFieldName": "Entity"
            },
            {
               "name": "DataObjects",
               "label": "DataObjects",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "SourceObject"
            },
            {
               "name": "IssuesForGroup",
               "label": "Issues",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCaseLink",
               "relatedTypeName": "Issue",
               "sourceFieldName": "Group"
            },
            {
               "name": "RisksForGroup",
               "label": "Risks",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCaseLink",
               "relatedTypeName": "Risk",
               "sourceFieldName": "Group"
            },
            {
               "name": "BugsForGroup",
               "label": "Bugs",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCaseLink",
               "relatedTypeName": "Bug",
               "sourceFieldName": "Group"
            },
            {
               "name": "EnhancementRequestForGroup",
               "label": "Enhancement Requests",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCaseLink",
               "relatedTypeName": "EnhancementRequest",
               "sourceFieldName": "Group"
            },
            {
               "name": "Documents",
               "label": "Files",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ResourceGroupEntityAttachmentLink",
               "relatedTypeName": "Document",
               "sourceFieldName": "Entity"
            },
            {
               "name": "LikedBy",
               "label": "Liked By",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Like",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "RecipientOfEmails",
               "label": "Recipient Of Emails",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "EmailRecipient",
               "sourceFieldName": "Recipient"
            },
            {
               "name": "SubGroups",
               "label": "Sub Groups",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "SubGroupHierarchyLink",
               "relatedTypeName": "UserGroup",
               "sourceFieldName": "Container"
            },
            {
               "name": "ParentGroups",
               "label": "Member of",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "SubGroupHierarchyLink",
               "relatedTypeName": "UserGroup",
               "sourceFieldName": "Member"
            },
            {
               "name": "Members",
               "label": "Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupHierarchyLink",
               "relatedTypeName": "ResourceEntity",
               "sourceFieldName": "Container"
            },
            {
               "name": "MemberOf",
               "label": "Member of (Obsolete)",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupHierarchyLink",
               "relatedTypeName": "UserGroup",
               "sourceFieldName": "Member"
            },
            {
               "name": "Skills",
               "label": "Skills",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "SkillLink",
               "relatedTypeName": "Skill",
               "sourceFieldName": "Member"
            },
            {
               "name": "AllMembers",
               "label": "All Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            }
         ]
      },
      {
         "typeName": "Skill",
         "relations": [
            {
               "name": "LikedBy",
               "label": "Liked By",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Like",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "UserGroups",
               "label": "Skill Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "SkillLink",
               "relatedTypeName": "ResourceEntity",
               "sourceFieldName": "Container"
            },
            {
               "name": "Documents",
               "label": "Files",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ResourceGroupEntityAttachmentLink",
               "relatedTypeName": "Document",
               "sourceFieldName": "Entity"
            }
         ]
      },
      {
         "typeName": "JobTitle",
         "relations": [
            {
               "name": "LikedBy",
               "label": "Liked By",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Like",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "WorkItems",
               "label": "Related Work Items (Obsolete)",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ResourceLink",
               "relatedTypeName": "GenericProject",
               "sourceFieldName": "Resource"
            },
            {
               "name": "ProvidesRateFor",
               "label": "Projects",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "JobTitleRateLink",
               "relatedTypeName": "GenericProject",
               "sourceFieldName": "Resource"
            },
            {
               "name": "Users",
               "label": "Job Title Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": "JobTitle"
            },
            {
               "name": "Documents",
               "label": "Files",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ResourceGroupEntityAttachmentLink",
               "relatedTypeName": "Document",
               "sourceFieldName": "Entity"
            }
         ]
      },
      {
         "typeName": "ResourceGroupEntity",
         "relations": [
            {
               "name": "Documents",
               "label": "Files",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ResourceGroupEntityAttachmentLink",
               "relatedTypeName": "Document",
               "sourceFieldName": "Entity"
            },
            {
               "name": "GroupMembers",
               "label": "Group Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupMembershipLink",
               "relatedTypeName": "User",
               "sourceFieldName": "Container"
            },
            {
               "name": "Projects",
               "label": "Projects",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupProjectLink",
               "relatedTypeName": "GenericProject",
               "sourceFieldName": "Group"
            },
            {
               "name": "Tasks",
               "label": "Tasks",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupTaskLink",
               "relatedTypeName": "GenericTask",
               "sourceFieldName": "Group"
            },
            {
               "name": "Customers",
               "label": "Customers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCustomerLink",
               "relatedTypeName": "Customer",
               "sourceFieldName": "Group"
            },
            {
               "name": "Cases",
               "label": "Cases",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCaseLink",
               "relatedTypeName": "Case",
               "sourceFieldName": "Group"
            },
            {
               "name": "Discussions",
               "label": "Discussions",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "",
               "relatedTypeName": "DiscussionPost",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Topics",
               "label": "Topics",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "TopicGroupLink",
               "relatedTypeName": "Topic",
               "sourceFieldName": "Entity"
            },
            {
               "name": "DataObjects",
               "label": "DataObjects",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "SourceObject"
            },
            {
               "name": "IssuesForGroup",
               "label": "Issues",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCaseLink",
               "relatedTypeName": "Issue",
               "sourceFieldName": "Group"
            },
            {
               "name": "RisksForGroup",
               "label": "Risks",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCaseLink",
               "relatedTypeName": "Risk",
               "sourceFieldName": "Group"
            },
            {
               "name": "BugsForGroup",
               "label": "Bugs",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCaseLink",
               "relatedTypeName": "Bug",
               "sourceFieldName": "Group"
            },
            {
               "name": "EnhancementRequestForGroup",
               "label": "Enhancement Requests",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCaseLink",
               "relatedTypeName": "EnhancementRequest",
               "sourceFieldName": "Group"
            },
            {
               "name": "LikedBy",
               "label": "Liked By",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Like",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "RecipientOfEmails",
               "label": "Recipient Of Emails",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "EmailRecipient",
               "sourceFieldName": "Recipient"
            },
            {
               "name": "SubGroups",
               "label": "Sub Groups",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "SubGroupHierarchyLink",
               "relatedTypeName": "UserGroup",
               "sourceFieldName": "Container"
            },
            {
               "name": "ParentGroups",
               "label": "Member of",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "SubGroupHierarchyLink",
               "relatedTypeName": "UserGroup",
               "sourceFieldName": "Member"
            },
            {
               "name": "Members",
               "label": "Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupHierarchyLink",
               "relatedTypeName": "ResourceEntity",
               "sourceFieldName": "Container"
            },
            {
               "name": "MemberOf",
               "label": "Member of (Obsolete)",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupHierarchyLink",
               "relatedTypeName": "UserGroup",
               "sourceFieldName": "Member"
            },
            {
               "name": "Skills",
               "label": "Skills",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "SkillLink",
               "relatedTypeName": "Skill",
               "sourceFieldName": "Member"
            },
            {
               "name": "AllMembers",
               "label": "All Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "UserGroups",
               "label": "Skill Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "SkillLink",
               "relatedTypeName": "ResourceEntity",
               "sourceFieldName": "Container"
            },
            {
               "name": "WorkItems",
               "label": "Related Work Items (Obsolete)",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ResourceLink",
               "relatedTypeName": "GenericProject",
               "sourceFieldName": "Resource"
            },
            {
               "name": "ProvidesRateFor",
               "label": "Projects",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "JobTitleRateLink",
               "relatedTypeName": "GenericProject",
               "sourceFieldName": "Resource"
            },
            {
               "name": "Users",
               "label": "Job Title Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": "JobTitle"
            }
         ]
      },
      {
         "typeName": "ResourceEntity",
         "relations": [
            {
               "name": "TechAccountManagerOfCustomers",
               "label": "Technical Account Manager of Customers",
               "roleLabel": "Customer Technical Account Manager",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Customer",
               "sourceFieldName": "TechnicalAccountManager"
            },
            {
               "name": "AccountOwnerOfCustomers",
               "label": "Account Owner of Customers",
               "roleLabel": "Customer Account Owner",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Customer",
               "sourceFieldName": "Owner"
            },
            {
               "name": "DirectFollowers",
               "label": "Direct Followers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Following",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Followers",
               "label": "Followers",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "UsersImFollowing",
               "label": "Users following",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "CreatedTimesheets",
               "label": "Created Timesheets",
               "roleLabel": "Creator",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Timesheet",
               "sourceFieldName": "CreatedBy"
            },
            {
               "name": "AttachedNotes",
               "label": "Notes",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Note",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "MemberOfWorkItems",
               "label": "Related Work Items",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "WorkItemTeamLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Resource"
            },
            {
               "name": "MemberOfGroups",
               "label": "Groups",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupMembershipLink",
               "relatedTypeName": "Group",
               "sourceFieldName": "Member"
            },
            {
               "name": "ApprovedTimesheets",
               "label": "Approved Timesheets",
               "roleLabel": "Approver",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Timesheet",
               "sourceFieldName": "ApprovedBy"
            },
            {
               "name": "OwnedExpenses",
               "label": "Owner of Expenses",
               "roleLabel": "Owner",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "ExpenseSheet",
               "sourceFieldName": "Owner"
            },
            {
               "name": "ExpensesApprovedBy",
               "label": "Approved Expenses",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "ExpenseSheet",
               "sourceFieldName": "ApprovedBy"
            },
            {
               "name": "ApproverOfExpenses",
               "label": "Approver of Expenses",
               "roleLabel": "Expense Approver",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "ExpenseSheet",
               "sourceFieldName": "Approver"
            },
            {
               "name": "OwnerOfIssues",
               "label": "Owned Cases",
               "roleLabel": "Owner",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "Owner"
            },
            {
               "name": "AssignedIssues",
               "label": "Assigned Cases",
               "roleLabel": "Assigned to",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "AssignedTo"
            },
            {
               "name": "SubmittedIssues",
               "label": "Submitted Cases",
               "roleLabel": "Submitted by",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "SubmittedBy"
            },
            {
               "name": "EvaluatedIssues",
               "label": "Evaluated Cases",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "EvaluatedBy"
            },
            {
               "name": "OpenedByIssues",
               "label": "Opened Cases",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "OpenedBy"
            },
            {
               "name": "ResolvedIssues",
               "label": "Resolved Cases",
               "roleLabel": "Resolved by",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "ResolvedBy"
            },
            {
               "name": "ClosedByIssues",
               "label": "Closed Cases",
               "roleLabel": "Closed by",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "ClosedBy"
            },
            {
               "name": "RejectedIssues",
               "label": "Rejected Cases",
               "roleLabel": "Rejected by",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "RejectedBy"
            },
            {
               "name": "ReopenedIssues",
               "label": "Reopened Cases",
               "roleLabel": "Reopened by",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "ReopenedBy"
            },
            {
               "name": "DeferredByIssues",
               "label": "Deferred Cases",
               "roleLabel": "Deferred by",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "DeferredBy"
            },
            {
               "name": "Issues",
               "label": "Member of Cases",
               "roleLabel": "Team Member",
               "readOnly": true,
               "linkTypeName": "IssueTeamMembers",
               "relatedTypeName": "Case",
               "sourceFieldName": "TeamMember"
            },
            {
               "name": "AssignedWorkItems",
               "label": "Assigned Work Items",
               "roleLabel": "Resource",
               "readOnly": true,
               "linkTypeName": "RegularResourceLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Resource"
            },
            {
               "name": "ReviewerOfWorkItems",
               "label": "Reviewer of Work Items",
               "roleLabel": "Reviewer",
               "readOnly": true,
               "linkTypeName": "ReviewerLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Resource"
            },
            {
               "name": "ManagerOfWorkItems",
               "label": "Managed Work Items",
               "roleLabel": "Owner",
               "readOnly": true,
               "linkTypeName": "ManagerResourceLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Resource"
            },
            {
               "name": "MemberOf",
               "label": "Member of (Obsolete)",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupHierarchyLink",
               "relatedTypeName": "Group",
               "sourceFieldName": "Member"
            },
            {
               "name": "Skills",
               "label": "Skills",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "SkillLink",
               "relatedTypeName": "Skill",
               "sourceFieldName": "Member"
            },
            {
               "name": "ProjectManagerOfProjects",
               "label": "Managed Projects",
               "roleLabel": "Project Manager",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "GenericProject",
               "sourceFieldName": "ProjectManager"
            },
            {
               "name": "ProjectSponsorOfProjects",
               "label": "Sponsored Projects",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "GenericProject",
               "sourceFieldName": "ProjectSponsor"
            },
            {
               "name": "Subordinates",
               "label": "Direct Reports",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": "DirectManager"
            },
            {
               "name": "WorkItems",
               "label": "Related Work Items (Obsolete)",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ResourceLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Resource"
            },
            {
               "name": "WorkItemIOpenedStopwatch",
               "label": "Active Stopwatches",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "Stopwatch",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "User"
            },
            {
               "name": "RecipientOfEmails",
               "label": "Recipient Of Emails",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "EmailRecipient",
               "sourceFieldName": "Recipient"
            },
            {
               "name": "Discussions",
               "label": "Discussions",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "",
               "relatedTypeName": "DiscussionPost",
               "sourceFieldName": "Entity"
            },
            {
               "name": "DirectManagerOfGroups",
               "label": "Manager of Groups",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "UserGroup",
               "sourceFieldName": "DirectManager"
            },
            {
               "name": "ReportedTimesheets",
               "label": "Reported Timesheets",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Timesheet",
               "sourceFieldName": "ReportedBy"
            },
            {
               "name": "OwnedProofs",
               "label": "Owned Proofs",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Document",
               "sourceFieldName": "ProofOwner"
            },
            {
               "name": "Documents",
               "label": "Files",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "UserAttachmentLink",
               "relatedTypeName": "Document",
               "sourceFieldName": "Entity"
            },
            {
               "name": "DataObjects",
               "label": "DataObjects",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "SourceObject"
            },
            {
               "name": "OwnedWorkItem",
               "label": "Owned Work Items",
               "roleLabel": "Owner",
               "readOnly": true,
               "linkTypeName": "OwnerLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Resource"
            },
            {
               "name": "UserOpenProofs",
               "label": "Open Proofs",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Document",
               "sourceFieldName": null
            },
            {
               "name": "ProgramManager",
               "label": "Managed Program Components",
               "roleLabel": "Program Manager Direct",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Program",
               "sourceFieldName": "ProgramManager"
            },
            {
               "name": "R_ResourceCost",
               "label": "Resource Cost",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "C_ResourceCost"
            },
            {
               "name": "R_LeaveEntitlements",
               "label": "Leave Entitlements",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "C_LeaveEntitlementfor"
            },
            {
               "name": "R_CustomerPortfolio",
               "label": "CustomerPortfolio",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Customer",
               "sourceFieldName": "C_CommercialManager"
            },
            {
               "name": "R_ManageAbsenceFor",
               "label": "Manage Absence For",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": "C_AbsenceManager"
            },
            {
               "name": "R_UserRate",
               "label": "User Rate",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "C_UserRate"
            },
            {
               "name": "R_AbsenceRequests",
               "label": "Absence Requests",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "C_AbsenceRequestsfor"
            },
            {
               "name": "ProfileUserGroups",
               "label": "Profile Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ProfileLink",
               "relatedTypeName": "ResourceEntity",
               "sourceFieldName": "Container"
            },
            {
               "name": "GroupMembers",
               "label": "Group Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupMembershipLink",
               "relatedTypeName": "User",
               "sourceFieldName": "Container"
            },
            {
               "name": "Projects",
               "label": "Projects",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupProjectLink",
               "relatedTypeName": "GenericProject",
               "sourceFieldName": "Group"
            },
            {
               "name": "Tasks",
               "label": "Tasks",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupTaskLink",
               "relatedTypeName": "GenericTask",
               "sourceFieldName": "Group"
            },
            {
               "name": "Customers",
               "label": "Customers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCustomerLink",
               "relatedTypeName": "Customer",
               "sourceFieldName": "Group"
            },
            {
               "name": "Cases",
               "label": "Cases",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCaseLink",
               "relatedTypeName": "Case",
               "sourceFieldName": "Group"
            },
            {
               "name": "Topics",
               "label": "Topics",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "TopicGroupLink",
               "relatedTypeName": "Topic",
               "sourceFieldName": "Entity"
            },
            {
               "name": "IssuesForGroup",
               "label": "Issues",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCaseLink",
               "relatedTypeName": "Issue",
               "sourceFieldName": "Group"
            },
            {
               "name": "RisksForGroup",
               "label": "Risks",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCaseLink",
               "relatedTypeName": "Risk",
               "sourceFieldName": "Group"
            },
            {
               "name": "BugsForGroup",
               "label": "Bugs",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCaseLink",
               "relatedTypeName": "Bug",
               "sourceFieldName": "Group"
            },
            {
               "name": "EnhancementRequestForGroup",
               "label": "Enhancement Requests",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCaseLink",
               "relatedTypeName": "EnhancementRequest",
               "sourceFieldName": "Group"
            },
            {
               "name": "LikedBy",
               "label": "Liked By",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Like",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "SubGroups",
               "label": "Sub Groups",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "SubGroupHierarchyLink",
               "relatedTypeName": "UserGroup",
               "sourceFieldName": "Container"
            },
            {
               "name": "ParentGroups",
               "label": "Member of",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "SubGroupHierarchyLink",
               "relatedTypeName": "UserGroup",
               "sourceFieldName": "Member"
            },
            {
               "name": "Members",
               "label": "Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupHierarchyLink",
               "relatedTypeName": "ResourceEntity",
               "sourceFieldName": "Container"
            },
            {
               "name": "AllMembers",
               "label": "All Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "UserGroups",
               "label": "Skill Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "SkillLink",
               "relatedTypeName": "ResourceEntity",
               "sourceFieldName": "Container"
            },
            {
               "name": "ProvidesRateFor",
               "label": "Projects",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "JobTitleRateLink",
               "relatedTypeName": "GenericProject",
               "sourceFieldName": "Resource"
            },
            {
               "name": "Users",
               "label": "Job Title Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": "JobTitle"
            }
         ]
      },
      {
         "typeName": "GenericResourceEntity",
         "relations": [
            {
               "name": "Discussions",
               "label": "Discussions",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "",
               "relatedTypeName": "DiscussionPost",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Documents",
               "label": "Files",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "NLRAttachmentLink",
               "relatedTypeName": "Document",
               "sourceFieldName": "Entity"
            },
            {
               "name": "NLROfWorkItems",
               "label": "Related Work Items",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "NonLaborResourceLinkAggregated",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "NonLaborResource"
            },
            {
               "name": "TechAccountManagerOfCustomers",
               "label": "Technical Account Manager of Customers",
               "roleLabel": "Customer Technical Account Manager",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Customer",
               "sourceFieldName": "TechnicalAccountManager"
            },
            {
               "name": "AccountOwnerOfCustomers",
               "label": "Account Owner of Customers",
               "roleLabel": "Customer Account Owner",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Customer",
               "sourceFieldName": "Owner"
            },
            {
               "name": "DirectFollowers",
               "label": "Direct Followers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Following",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Followers",
               "label": "Followers",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "UsersImFollowing",
               "label": "Users following",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "CreatedTimesheets",
               "label": "Created Timesheets",
               "roleLabel": "Creator",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Timesheet",
               "sourceFieldName": "CreatedBy"
            },
            {
               "name": "AttachedNotes",
               "label": "Notes",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Note",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "MemberOfWorkItems",
               "label": "Related Work Items",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "WorkItemTeamLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Resource"
            },
            {
               "name": "MemberOfGroups",
               "label": "Groups",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupMembershipLink",
               "relatedTypeName": "Group",
               "sourceFieldName": "Member"
            },
            {
               "name": "ApprovedTimesheets",
               "label": "Approved Timesheets",
               "roleLabel": "Approver",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Timesheet",
               "sourceFieldName": "ApprovedBy"
            },
            {
               "name": "OwnedExpenses",
               "label": "Owner of Expenses",
               "roleLabel": "Owner",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "ExpenseSheet",
               "sourceFieldName": "Owner"
            },
            {
               "name": "ExpensesApprovedBy",
               "label": "Approved Expenses",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "ExpenseSheet",
               "sourceFieldName": "ApprovedBy"
            },
            {
               "name": "ApproverOfExpenses",
               "label": "Approver of Expenses",
               "roleLabel": "Expense Approver",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "ExpenseSheet",
               "sourceFieldName": "Approver"
            },
            {
               "name": "OwnerOfIssues",
               "label": "Owned Cases",
               "roleLabel": "Owner",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "Owner"
            },
            {
               "name": "AssignedIssues",
               "label": "Assigned Cases",
               "roleLabel": "Assigned to",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "AssignedTo"
            },
            {
               "name": "SubmittedIssues",
               "label": "Submitted Cases",
               "roleLabel": "Submitted by",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "SubmittedBy"
            },
            {
               "name": "EvaluatedIssues",
               "label": "Evaluated Cases",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "EvaluatedBy"
            },
            {
               "name": "OpenedByIssues",
               "label": "Opened Cases",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "OpenedBy"
            },
            {
               "name": "ResolvedIssues",
               "label": "Resolved Cases",
               "roleLabel": "Resolved by",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "ResolvedBy"
            },
            {
               "name": "ClosedByIssues",
               "label": "Closed Cases",
               "roleLabel": "Closed by",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "ClosedBy"
            },
            {
               "name": "RejectedIssues",
               "label": "Rejected Cases",
               "roleLabel": "Rejected by",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "RejectedBy"
            },
            {
               "name": "ReopenedIssues",
               "label": "Reopened Cases",
               "roleLabel": "Reopened by",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "ReopenedBy"
            },
            {
               "name": "DeferredByIssues",
               "label": "Deferred Cases",
               "roleLabel": "Deferred by",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "DeferredBy"
            },
            {
               "name": "Issues",
               "label": "Member of Cases",
               "roleLabel": "Team Member",
               "readOnly": true,
               "linkTypeName": "IssueTeamMembers",
               "relatedTypeName": "Case",
               "sourceFieldName": "TeamMember"
            },
            {
               "name": "AssignedWorkItems",
               "label": "Assigned Work Items",
               "roleLabel": "Resource",
               "readOnly": true,
               "linkTypeName": "RegularResourceLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Resource"
            },
            {
               "name": "ReviewerOfWorkItems",
               "label": "Reviewer of Work Items",
               "roleLabel": "Reviewer",
               "readOnly": true,
               "linkTypeName": "ReviewerLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Resource"
            },
            {
               "name": "ManagerOfWorkItems",
               "label": "Managed Work Items",
               "roleLabel": "Manager",
               "readOnly": true,
               "linkTypeName": "ManagerResourceLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Resource"
            },
            {
               "name": "MemberOf",
               "label": "Member of (Obsolete)",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupHierarchyLink",
               "relatedTypeName": "Group",
               "sourceFieldName": "Member"
            },
            {
               "name": "Skills",
               "label": "Skills",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "SkillLink",
               "relatedTypeName": "Skill",
               "sourceFieldName": "Member"
            },
            {
               "name": "ProjectManagerOfProjects",
               "label": "Managed Projects",
               "roleLabel": "Project Manager",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "GenericProject",
               "sourceFieldName": "ProjectManager"
            },
            {
               "name": "ProjectSponsorOfProjects",
               "label": "Sponsored Projects",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "GenericProject",
               "sourceFieldName": "ProjectSponsor"
            },
            {
               "name": "Subordinates",
               "label": "Direct Reports",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": "DirectManager"
            },
            {
               "name": "WorkItems",
               "label": "Related Work Items (Obsolete)",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ResourceLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Resource"
            },
            {
               "name": "WorkItemIOpenedStopwatch",
               "label": "Active Stopwatches",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "Stopwatch",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "User"
            },
            {
               "name": "RecipientOfEmails",
               "label": "Recipient Of Emails",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "EmailRecipient",
               "sourceFieldName": "Recipient"
            },
            {
               "name": "DirectManagerOfGroups",
               "label": "Manager of Groups",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "UserGroup",
               "sourceFieldName": "DirectManager"
            },
            {
               "name": "ReportedTimesheets",
               "label": "Reported Timesheets",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Timesheet",
               "sourceFieldName": "ReportedBy"
            },
            {
               "name": "OwnedProofs",
               "label": "Owned Proofs",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Document",
               "sourceFieldName": "ProofOwner"
            },
            {
               "name": "DataObjects",
               "label": "DataObjects",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "SourceObject"
            },
            {
               "name": "OwnedWorkItem",
               "label": "Owned Work Items",
               "roleLabel": "Owner",
               "readOnly": true,
               "linkTypeName": "OwnerLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Resource"
            },
            {
               "name": "UserOpenProofs",
               "label": "Open Proofs",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Document",
               "sourceFieldName": null
            },
            {
               "name": "ProgramManager",
               "label": "Managed Program Components",
               "roleLabel": "Program Manager Direct",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Program",
               "sourceFieldName": "ProgramManager"
            },
            {
               "name": "R_ResourceCost",
               "label": "Resource Cost",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "C_ResourceCost"
            },
            {
               "name": "R_LeaveEntitlements",
               "label": "Leave Entitlements",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "C_LeaveEntitlementfor"
            },
            {
               "name": "R_CustomerPortfolio",
               "label": "CustomerPortfolio",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Customer",
               "sourceFieldName": "C_CommercialManager"
            },
            {
               "name": "R_ManageAbsenceFor",
               "label": "Manage Absence For",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": "C_AbsenceManager"
            },
            {
               "name": "R_UserRate",
               "label": "User Rate",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "C_UserRate"
            },
            {
               "name": "R_AbsenceRequests",
               "label": "Absence Requests",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "C_AbsenceRequestsfor"
            },
            {
               "name": "ProfileUserGroups",
               "label": "Profile Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ProfileLink",
               "relatedTypeName": "ResourceEntity",
               "sourceFieldName": "Container"
            },
            {
               "name": "GroupMembers",
               "label": "Group Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupMembershipLink",
               "relatedTypeName": "User",
               "sourceFieldName": "Container"
            },
            {
               "name": "Projects",
               "label": "Projects",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupProjectLink",
               "relatedTypeName": "GenericProject",
               "sourceFieldName": "Group"
            },
            {
               "name": "Tasks",
               "label": "Tasks",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupTaskLink",
               "relatedTypeName": "GenericTask",
               "sourceFieldName": "Group"
            },
            {
               "name": "Customers",
               "label": "Customers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCustomerLink",
               "relatedTypeName": "Customer",
               "sourceFieldName": "Group"
            },
            {
               "name": "Cases",
               "label": "Cases",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCaseLink",
               "relatedTypeName": "Case",
               "sourceFieldName": "Group"
            },
            {
               "name": "Topics",
               "label": "Topics",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "TopicGroupLink",
               "relatedTypeName": "Topic",
               "sourceFieldName": "Entity"
            },
            {
               "name": "IssuesForGroup",
               "label": "Issues",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCaseLink",
               "relatedTypeName": "Issue",
               "sourceFieldName": "Group"
            },
            {
               "name": "RisksForGroup",
               "label": "Risks",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCaseLink",
               "relatedTypeName": "Risk",
               "sourceFieldName": "Group"
            },
            {
               "name": "BugsForGroup",
               "label": "Bugs",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCaseLink",
               "relatedTypeName": "Bug",
               "sourceFieldName": "Group"
            },
            {
               "name": "EnhancementRequestForGroup",
               "label": "Enhancement Requests",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCaseLink",
               "relatedTypeName": "EnhancementRequest",
               "sourceFieldName": "Group"
            },
            {
               "name": "LikedBy",
               "label": "Liked By",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Like",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "SubGroups",
               "label": "Sub Groups",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "SubGroupHierarchyLink",
               "relatedTypeName": "UserGroup",
               "sourceFieldName": "Container"
            },
            {
               "name": "ParentGroups",
               "label": "Member of",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "SubGroupHierarchyLink",
               "relatedTypeName": "UserGroup",
               "sourceFieldName": "Member"
            },
            {
               "name": "Members",
               "label": "Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupHierarchyLink",
               "relatedTypeName": "ResourceEntity",
               "sourceFieldName": "Container"
            },
            {
               "name": "AllMembers",
               "label": "All Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "UserGroups",
               "label": "Skill Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "SkillLink",
               "relatedTypeName": "ResourceEntity",
               "sourceFieldName": "Container"
            },
            {
               "name": "ProvidesRateFor",
               "label": "Projects",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "JobTitleRateLink",
               "relatedTypeName": "GenericProject",
               "sourceFieldName": "Resource"
            },
            {
               "name": "Users",
               "label": "Job Title Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": "JobTitle"
            }
         ]
      },
      {
         "typeName": "FileTemplate",
         "relations": []
      },
      {
         "typeName": "Document",
         "relations": [
            {
               "name": "LikedBy",
               "label": "Liked By",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Like",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "DirectFollowers",
               "label": "Direct Followers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Following",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Followers",
               "label": "Followers",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "Groups",
               "label": "Groups",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ResourceGroupEntityAttachmentLink",
               "relatedTypeName": "ResourceGroupEntity",
               "sourceFieldName": "Document"
            },
            {
               "name": "DiscussionMessages",
               "label": "DiscussionMessages",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "DiscussionMessageAttachmentLink",
               "relatedTypeName": "DiscussionMessage",
               "sourceFieldName": "Document"
            },
            {
               "name": "Customers",
               "label": "Customers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "CustomerAttachmentLink",
               "relatedTypeName": "Customer",
               "sourceFieldName": "Document"
            },
            {
               "name": "ExpenseSheets",
               "label": "Expense Sheets",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ExpenseSheetAttachmentLink",
               "relatedTypeName": "ExpenseSheet",
               "sourceFieldName": "Document"
            },
            {
               "name": "Discussions",
               "label": "Discussions",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "",
               "relatedTypeName": "DiscussionPost",
               "sourceFieldName": "Entity"
            },
            {
               "name": "WorkItems",
               "label": "Work Items",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "WorkItemAttachmentLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Document"
            },
            {
               "name": "ExpenseEntries",
               "label": "Expenses",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ExpenseEntryAttachmentLink",
               "relatedTypeName": "Expense",
               "sourceFieldName": "Document"
            },
            {
               "name": "Issues",
               "label": "Cases",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "IssueAttachmentLink",
               "relatedTypeName": "Case",
               "sourceFieldName": "Document"
            },
            {
               "name": "Topics",
               "label": "Topics",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "TopicDocumentLink",
               "relatedTypeName": "Topic",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Users",
               "label": "Users",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "UserAttachmentLink",
               "relatedTypeName": "User",
               "sourceFieldName": "Document"
            },
            {
               "name": "ProofReviewers",
               "label": "Proof Reviewers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ProofReviewer",
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "Reports",
               "label": "Reports",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ReportAttachmentLink",
               "relatedTypeName": "Report",
               "sourceFieldName": "Document"
            },
            {
               "name": "Dashboards",
               "label": "Dashboards",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "DashboardAttachmentLink",
               "relatedTypeName": "Dashboard",
               "sourceFieldName": "Document"
            },
            {
               "name": "Lines",
               "label": "Lines",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "String",
               "sourceFieldName": null
            },
            {
               "name": "DataObjects",
               "label": "DataObjects",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "SourceObject"
            },
            {
               "name": "NonLaborResource",
               "label": "Non-Labor Resource",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "NLRAttachmentLink",
               "relatedTypeName": "NonLaborResource",
               "sourceFieldName": "Document"
            }
         ]
      },
      {
         "typeName": "BaseFile",
         "relations": [
            {
               "name": "LikedBy",
               "label": "Liked By",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Like",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "DirectFollowers",
               "label": "Direct Followers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Following",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Followers",
               "label": "Followers",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "Groups",
               "label": "Groups",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ResourceGroupEntityAttachmentLink",
               "relatedTypeName": "ResourceGroupEntity",
               "sourceFieldName": "Document"
            },
            {
               "name": "DiscussionMessages",
               "label": "DiscussionMessages",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "DiscussionMessageAttachmentLink",
               "relatedTypeName": "DiscussionMessage",
               "sourceFieldName": "Document"
            },
            {
               "name": "Customers",
               "label": "Customers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "CustomerAttachmentLink",
               "relatedTypeName": "Customer",
               "sourceFieldName": "Document"
            },
            {
               "name": "ExpenseSheets",
               "label": "Expense Sheets",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ExpenseSheetAttachmentLink",
               "relatedTypeName": "ExpenseSheet",
               "sourceFieldName": "Document"
            },
            {
               "name": "Discussions",
               "label": "Discussions",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "",
               "relatedTypeName": "DiscussionPost",
               "sourceFieldName": "Entity"
            },
            {
               "name": "WorkItems",
               "label": "Work Items",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "WorkItemAttachmentLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Document"
            },
            {
               "name": "ExpenseEntries",
               "label": "Expenses",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ExpenseEntryAttachmentLink",
               "relatedTypeName": "Expense",
               "sourceFieldName": "Document"
            },
            {
               "name": "Issues",
               "label": "Cases",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "IssueAttachmentLink",
               "relatedTypeName": "Case",
               "sourceFieldName": "Document"
            },
            {
               "name": "Topics",
               "label": "Topics",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "TopicDocumentLink",
               "relatedTypeName": "Topic",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Users",
               "label": "Users",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "UserAttachmentLink",
               "relatedTypeName": "User",
               "sourceFieldName": "Document"
            },
            {
               "name": "ProofReviewers",
               "label": "Proof Reviewers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ProofReviewer",
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "Reports",
               "label": "Reports",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ReportAttachmentLink",
               "relatedTypeName": "Report",
               "sourceFieldName": "Document"
            },
            {
               "name": "Dashboards",
               "label": "Dashboards",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "DashboardAttachmentLink",
               "relatedTypeName": "Dashboard",
               "sourceFieldName": "Document"
            },
            {
               "name": "Lines",
               "label": "Lines",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "String",
               "sourceFieldName": null
            },
            {
               "name": "DataObjects",
               "label": "DataObjects",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "SourceObject"
            },
            {
               "name": "NonLaborResource",
               "label": "Non labor resource",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "NLRAttachmentLink",
               "relatedTypeName": "NonLaborResource",
               "sourceFieldName": "Document"
            }
         ]
      },
      {
         "typeName": "LaborResourceLinkAggregated",
         "relations": [
            {
               "name": "TimePhaseData",
               "label": "Time phase data",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "LaborResourceTimePhase",
               "sourceFieldName": "RelatedLink"
            }
         ]
      },
      {
         "typeName": "LaborResourceLinkDirect",
         "relations": [
            {
               "name": "TimePhaseData",
               "label": "Time phase data",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "LaborResourceTimePhase",
               "sourceFieldName": "RelatedLink"
            }
         ]
      },
      {
         "typeName": "LaborResourceLink",
         "relations": [
            {
               "name": "TimePhaseData",
               "label": "Time phase data",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "LaborResourceTimePhase",
               "sourceFieldName": "RelatedLink"
            }
         ]
      },
      {
         "typeName": "NonLaborResourceLinkAggregated",
         "relations": [
            {
               "name": "TimePhaseData",
               "label": "Time phase data",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "ResourceTimePhase",
               "sourceFieldName": "RelatedLink"
            }
         ]
      },
      {
         "typeName": "NonLaborResourceLinkDirect",
         "relations": [
            {
               "name": "TimePhaseData",
               "label": "Time phase data",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "ResourceTimePhase",
               "sourceFieldName": "RelatedLink"
            }
         ]
      },
      {
         "typeName": "NonLaborResourceLink",
         "relations": [
            {
               "name": "TimePhaseData",
               "label": "Time phase data",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "ResourceTimePhase",
               "sourceFieldName": "RelatedLink"
            }
         ]
      },
      {
         "typeName": "ResourceLinkFinancial",
         "relations": [
            {
               "name": "TimePhaseData",
               "label": "Time phase data",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "LaborResourceTimePhase",
               "sourceFieldName": "RelatedLink"
            }
         ]
      },
      {
         "typeName": "LaborResourceTimePhase",
         "relations": []
      },
      {
         "typeName": "NonLaborResourceTimePhase",
         "relations": []
      },
      {
         "typeName": "ResourceTimePhase",
         "relations": []
      },
      {
         "typeName": "LaborResourceSnapshot",
         "relations": []
      },
      {
         "typeName": "AdditionalObjectProperties",
         "relations": []
      },
      {
         "typeName": "PushNotification",
         "relations": []
      },
      {
         "typeName": "Data",
         "relations": [
            {
               "name": "R_RoleRates",
               "label": "RoleRates",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Organization",
               "sourceFieldName": "C_RolesRates"
            },
            {
               "name": "R_AbsenceRequests",
               "label": "Absence Requests",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "C_AbsenceEntitlement"
            },
            {
               "name": "R_SalaryLink",
               "label": "Salary Link",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "C_Salary"
            }
         ]
      },
      {
         "typeName": "WorkByDay",
         "relations": []
      },
      {
         "typeName": "ResourceCalendarExceptionAbsolute",
         "relations": []
      },
      {
         "typeName": "ResourceCalendarExceptionRelative",
         "relations": []
      },
      {
         "typeName": "ResourceCalendarException",
         "relations": []
      },
      {
         "typeName": "ReportShortcutLink",
         "relations": []
      },
      {
         "typeName": "ReportsHierarchyLink",
         "relations": []
      },
      {
         "typeName": "ReportsFolderContentLink",
         "relations": []
      },
      {
         "typeName": "FolderContentLink",
         "relations": []
      },
      {
         "typeName": "Dashboard",
         "relations": [
            {
               "name": "AttachedEmails",
               "label": "Emails",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Email",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "Documents",
               "label": "Snapshots",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "DashboardAttachmentLink",
               "relatedTypeName": "Document",
               "sourceFieldName": "Entity"
            },
            {
               "name": "DirectFollowers",
               "label": "Direct Followers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Following",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Followers",
               "label": "Followers",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "PermisionDefinitions",
               "label": "Permission Definitions",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Permission",
               "relatedTypeName": "ResourceEntity",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Discussions",
               "label": "Discussions",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "",
               "relatedTypeName": "DiscussionPost",
               "sourceFieldName": "Entity"
            },
            {
               "name": "DataObjects",
               "label": "DataObjects",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "SourceObject"
            }
         ]
      },
      {
         "typeName": "Report",
         "relations": [
            {
               "name": "AttachedEmails",
               "label": "Emails",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Email",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "Documents",
               "label": "Snapshots",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "ReportAttachmentLink",
               "relatedTypeName": "Document",
               "sourceFieldName": "Entity"
            },
            {
               "name": "DirectFollowers",
               "label": "Direct Followers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Following",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Followers",
               "label": "Followers",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "PermisionDefinitions",
               "label": "Permission Definitions",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Permission",
               "relatedTypeName": "ResourceEntity",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Discussions",
               "label": "Discussions",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "",
               "relatedTypeName": "DiscussionPost",
               "sourceFieldName": "Entity"
            },
            {
               "name": "DataObjects",
               "label": "DataObjects",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "SourceObject"
            }
         ]
      },
      {
         "typeName": "ReportAndDashboard",
         "relations": [
            {
               "name": "DirectFollowers",
               "label": "Direct Followers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Following",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Followers",
               "label": "Followers",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "PermisionDefinitions",
               "label": "Permission Definitions",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Permission",
               "relatedTypeName": "ResourceEntity",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Discussions",
               "label": "Discussions",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "",
               "relatedTypeName": "DiscussionPost",
               "sourceFieldName": "Entity"
            },
            {
               "name": "DataObjects",
               "label": "DataObjects",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "SourceObject"
            },
            {
               "name": "AttachedEmails",
               "label": "Emails",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Email",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "Documents",
               "label": "Snapshots",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "DashboardAttachmentLink",
               "relatedTypeName": "Document",
               "sourceFieldName": "Entity"
            }
         ]
      },
      {
         "typeName": "FolderForReport",
         "relations": [
            {
               "name": "AllSubItems",
               "label": "All Sub Items",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "FolderContentLink",
               "relatedTypeName": "ReportAndDashboard",
               "sourceFieldName": "Parent"
            },
            {
               "name": "ReportsInFolder",
               "label": "Reports in Folder",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "ReportsHierarchyLink",
               "relatedTypeName": "ReportAndDashboard",
               "sourceFieldName": "Parent"
            },
            {
               "name": "PermisionDefinitions",
               "label": "Permission Definitions",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Permission",
               "relatedTypeName": "ResourceEntity",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Discussions",
               "label": "Discussions",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "",
               "relatedTypeName": "DiscussionPost",
               "sourceFieldName": "Entity"
            },
            {
               "name": "DataObjects",
               "label": "DataObjects",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "SourceObject"
            }
         ]
      },
      {
         "typeName": "FoldersAndReports",
         "relations": [
            {
               "name": "PermisionDefinitions",
               "label": "Permission Definitions",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Permission",
               "relatedTypeName": "ResourceEntity",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Discussions",
               "label": "Discussions",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "",
               "relatedTypeName": "DiscussionPost",
               "sourceFieldName": "Entity"
            },
            {
               "name": "DataObjects",
               "label": "DataObjects",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "SourceObject"
            },
            {
               "name": "DirectFollowers",
               "label": "Direct Followers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Following",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Followers",
               "label": "Followers",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "AttachedEmails",
               "label": "Emails",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Email",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "Documents",
               "label": "Files",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "DashboardAttachmentLink",
               "relatedTypeName": "Document",
               "sourceFieldName": "Entity"
            },
            {
               "name": "AllSubItems",
               "label": "All Sub Items",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "FolderContentLink",
               "relatedTypeName": "ReportAndDashboard",
               "sourceFieldName": "Parent"
            },
            {
               "name": "ReportsInFolder",
               "label": "Reports in Folder",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "ReportsHierarchyLink",
               "relatedTypeName": "ReportAndDashboard",
               "sourceFieldName": "Parent"
            }
         ]
      },
      {
         "typeName": "Permission",
         "relations": []
      },
      {
         "typeName": "DependencyLink",
         "relations": []
      },
      {
         "typeName": "IntegrationsRegistry",
         "relations": []
      },
      {
         "typeName": "TopicDocumentLink",
         "relations": []
      },
      {
         "typeName": "TopicDiscussionLink",
         "relations": []
      },
      {
         "typeName": "TopicGroupLink",
         "relations": []
      },
      {
         "typeName": "TopicExpenseEntryLink",
         "relations": []
      },
      {
         "typeName": "TopicExpenseSheetLink",
         "relations": []
      },
      {
         "typeName": "TopicCustomerLink",
         "relations": []
      },
      {
         "typeName": "TopicCaseLink",
         "relations": []
      },
      {
         "typeName": "TopicWorkItemLink",
         "relations": []
      },
      {
         "typeName": "TopicLink",
         "relations": []
      },
      {
         "typeName": "Milestone",
         "relations": [
            {
               "name": "AllImpacting",
               "label": "Impacting and Sub Items",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "WorkItemHierarchyLink",
               "relatedTypeName": "PlanningComponent",
               "sourceFieldName": "Parent"
            },
            {
               "name": "Tasks",
               "label": "Tasks",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "GenericTask",
               "sourceFieldName": "Milestone"
            },
            {
               "name": "Children",
               "label": "Sub Items",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "RealWorkItemHierarchyLink",
               "relatedTypeName": "GenericTask",
               "sourceFieldName": "Parent"
            },
            {
               "name": "Shortcuts",
               "label": "Shortcuts",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "ShortcutLink",
               "relatedTypeName": "PlanningComponent",
               "sourceFieldName": "Parent"
            },
            {
               "name": "Impacting",
               "label": "Impacting",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ProgressImpactLink",
               "relatedTypeName": "PlanningComponent",
               "sourceFieldName": "Parent"
            },
            {
               "name": "DirectNonLaborResources",
               "label": "Non-Labor Resources",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "NonLaborResourceLinkDirect",
               "relatedTypeName": "NonLaborResource",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "AggregatedNonLaborResources",
               "label": "Aggregated Non-Labor Resources",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "NonLaborResourceLinkAggregated",
               "relatedTypeName": "NonLaborResource",
               "sourceFieldName": null
            },
            {
               "name": "AllImpacted",
               "label": "Impacted and Parents",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "WorkItemHierarchyLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Child"
            },
            {
               "name": "WhereUsedAsShortcut",
               "label": "Shortcut in",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "ShortcutLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Child"
            },
            {
               "name": "ImpactedBy",
               "label": "Impacted By",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "ProgressImpactLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Child"
            },
            {
               "name": "DirectFollowers",
               "label": "Direct Followers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Following",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "RelatedExpenses",
               "label": "Aggregated Expenses",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Expense",
               "sourceFieldName": null
            },
            {
               "name": "Followers",
               "label": "Followers",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "ProjectCustomers",
               "label": "Project Customers",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Customer",
               "sourceFieldName": null
            },
            {
               "name": "TeamMembers",
               "label": "Work Item Team Members",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "WorkItemTeamLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "AttachedPosts",
               "label": "V5 Posts",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Post",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "AttachedNotes",
               "label": "Notes",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Note",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "AttachedEmails",
               "label": "Emails",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Email",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "RelatedTimesheetEntries",
               "label": "Time Entries",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Timesheet",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Expenses",
               "label": "Expenses",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Expense",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "OriginatedIssues",
               "label": "Originated Cases",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "OriginatedFrom"
            },
            {
               "name": "Issues",
               "label": "Cases",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "Case",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Resources",
               "label": "Resources",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RegularResourceLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Reviewers",
               "label": "Reviewers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ReviewerLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Managers",
               "label": "Managers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ManagerResourceLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Discussions",
               "label": "Discussions",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "",
               "relatedTypeName": "DiscussionPost",
               "sourceFieldName": "Entity"
            },
            {
               "name": "LikedBy",
               "label": "Liked By",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Like",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "AllTeamMembers",
               "label": "All Team Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "AllManagers",
               "label": "All Managers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "AllReviewers",
               "label": "All Reviewers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "AllResources",
               "label": "All Resources",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "Successors",
               "label": "Successors",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "DependencyLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Predecessors",
               "label": "Predecessors",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "DependencyLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "DependsOn"
            },
            {
               "name": "AllTeam",
               "label": "Team Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ResourceLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Documents",
               "label": "Files",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "WorkItemAttachmentLink",
               "relatedTypeName": "Document",
               "sourceFieldName": "Entity"
            },
            {
               "name": "UsersOpenedStopwatches",
               "label": "Active Stopwatch Users",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "Stopwatch",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Topics",
               "label": "Topics",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "TopicWorkItemLink",
               "relatedTypeName": "Topic",
               "sourceFieldName": "Entity"
            },
            {
               "name": "DataObjects",
               "label": "DataObjects",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "SourceObject"
            },
            {
               "name": "RelatedIssues",
               "label": "Issues",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "Issue",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "RelatedRisks",
               "label": "Risks",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "Risk",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "RelatedBugs",
               "label": "Bugs",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "Bug",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "RelatedRequests",
               "label": "Requests",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "EnhancementRequest",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "PermisionDefinitions",
               "label": "Permission Definitions",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Permission",
               "relatedTypeName": "ResourceEntity",
               "sourceFieldName": "Entity"
            },
            {
               "name": "AdditionalObjectProperties",
               "label": "Overview",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "AdditionalObjectProperties",
               "sourceFieldName": "RelatedItem"
            },
            {
               "name": "R_ProjectCost",
               "label": "ProjectCost",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "C_ProjectCosts"
            },
            {
               "name": "R_ActionItemsFor",
               "label": "Action Items",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "GenericTask",
               "sourceFieldName": "C_ActionItemsfor"
            }
         ]
      },
      {
         "typeName": "Task",
         "relations": [
            {
               "name": "DirectLaborResources",
               "label": "Labor Resources",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "LaborResourceLinkDirect",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "DirectNonLaborResources",
               "label": "Non-Labor Resources",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "NonLaborResourceLinkDirect",
               "relatedTypeName": "NonLaborResource",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "FinancialResources",
               "label": "Financial Resources",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ResourceLinkFinancial",
               "relatedTypeName": "GenericResourceEntity",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Groups",
               "label": "Groups",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupTaskLink",
               "relatedTypeName": "Group",
               "sourceFieldName": "Entity"
            },
            {
               "name": "AllImpacting",
               "label": "Impacting and Sub Items",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "WorkItemHierarchyLink",
               "relatedTypeName": "GenericTask",
               "sourceFieldName": "Parent"
            },
            {
               "name": "Children",
               "label": "Sub Items",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "RealWorkItemHierarchyLink",
               "relatedTypeName": "GenericTask",
               "sourceFieldName": "Parent"
            },
            {
               "name": "Shortcuts",
               "label": "Shortcuts",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "ShortcutLink",
               "relatedTypeName": "GenericTask",
               "sourceFieldName": "Parent"
            },
            {
               "name": "Impacting",
               "label": "Impacting",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ProgressImpactLink",
               "relatedTypeName": "GenericTask",
               "sourceFieldName": "Parent"
            },
            {
               "name": "R_TaskFinancials",
               "label": "Monthly Task Breakdown",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "C_ParentTask"
            },
            {
               "name": "AllImpacted",
               "label": "Impacted and Parents",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "WorkItemHierarchyLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Child"
            },
            {
               "name": "WhereUsedAsShortcut",
               "label": "Shortcut in",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "ShortcutLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Child"
            },
            {
               "name": "ImpactedBy",
               "label": "Impacted By",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "ProgressImpactLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Child"
            },
            {
               "name": "DirectFollowers",
               "label": "Direct Followers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Following",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "RelatedExpenses",
               "label": "Aggregated Expenses",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Expense",
               "sourceFieldName": null
            },
            {
               "name": "Followers",
               "label": "Followers",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "ProjectCustomers",
               "label": "Project Customers",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Customer",
               "sourceFieldName": null
            },
            {
               "name": "TeamMembers",
               "label": "Work Item Team Members",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "WorkItemTeamLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "AttachedPosts",
               "label": "V5 Posts",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Post",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "AttachedNotes",
               "label": "Notes",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Note",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "AttachedEmails",
               "label": "Emails",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Email",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "RelatedTimesheetEntries",
               "label": "Time Entries",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Timesheet",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Expenses",
               "label": "Expenses",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Expense",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "OriginatedIssues",
               "label": "Originated Cases",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "OriginatedFrom"
            },
            {
               "name": "Issues",
               "label": "Cases",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "Case",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Resources",
               "label": "Resources",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RegularResourceLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Reviewers",
               "label": "Reviewers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ReviewerLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Managers",
               "label": "Managers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ManagerResourceLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Discussions",
               "label": "Discussions",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "",
               "relatedTypeName": "DiscussionPost",
               "sourceFieldName": "Entity"
            },
            {
               "name": "LikedBy",
               "label": "Liked By",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Like",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "AllTeamMembers",
               "label": "All Team Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "AllManagers",
               "label": "All Managers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "AllReviewers",
               "label": "All Reviewers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "AllResources",
               "label": "All Resources",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "Successors",
               "label": "Successors",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "DependencyLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Predecessors",
               "label": "Predecessors",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "DependencyLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "DependsOn"
            },
            {
               "name": "AllTeam",
               "label": "Team Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ResourceLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Documents",
               "label": "Files",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "WorkItemAttachmentLink",
               "relatedTypeName": "Document",
               "sourceFieldName": "Entity"
            },
            {
               "name": "UsersOpenedStopwatches",
               "label": "Active Stopwatch Users",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "Stopwatch",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Topics",
               "label": "Topics",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "TopicWorkItemLink",
               "relatedTypeName": "Topic",
               "sourceFieldName": "Entity"
            },
            {
               "name": "DataObjects",
               "label": "DataObjects",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "SourceObject"
            },
            {
               "name": "RelatedIssues",
               "label": "Issues",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "Issue",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "RelatedRisks",
               "label": "Risks",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "Risk",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "RelatedBugs",
               "label": "Bugs",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "Bug",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "RelatedRequests",
               "label": "Requests",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "EnhancementRequest",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "PermisionDefinitions",
               "label": "Permission Definitions",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Permission",
               "relatedTypeName": "ResourceEntity",
               "sourceFieldName": "Entity"
            },
            {
               "name": "AdditionalObjectProperties",
               "label": "Overview",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "AdditionalObjectProperties",
               "sourceFieldName": "RelatedItem"
            },
            {
               "name": "R_ProjectCost",
               "label": "ProjectCost",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "C_ProjectCosts"
            },
            {
               "name": "R_ActionItemsFor",
               "label": "Action Items",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "GenericTask",
               "sourceFieldName": "C_ActionItemsfor"
            }
         ]
      },
      {
         "typeName": "RecurringTask",
         "relations": [
            {
               "name": "Groups",
               "label": "Groups",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupTaskLink",
               "relatedTypeName": "Group",
               "sourceFieldName": "Entity"
            },
            {
               "name": "AllImpacting",
               "label": "Impacting and Sub Items",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "WorkItemHierarchyLink",
               "relatedTypeName": "GenericTask",
               "sourceFieldName": "Parent"
            },
            {
               "name": "Children",
               "label": "Sub Items",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "RealWorkItemHierarchyLink",
               "relatedTypeName": "GenericTask",
               "sourceFieldName": "Parent"
            },
            {
               "name": "Shortcuts",
               "label": "Shortcuts",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "ShortcutLink",
               "relatedTypeName": "GenericTask",
               "sourceFieldName": "Parent"
            },
            {
               "name": "Impacting",
               "label": "Impacting",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ProgressImpactLink",
               "relatedTypeName": "GenericTask",
               "sourceFieldName": "Parent"
            },
            {
               "name": "R_TaskFinancials",
               "label": "Monthly Task Breakdown",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "C_ParentTask"
            },
            {
               "name": "AllImpacted",
               "label": "Impacted and Parents",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "WorkItemHierarchyLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Child"
            },
            {
               "name": "WhereUsedAsShortcut",
               "label": "Shortcut in",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "ShortcutLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Child"
            },
            {
               "name": "ImpactedBy",
               "label": "Impacted By",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "ProgressImpactLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Child"
            },
            {
               "name": "DirectFollowers",
               "label": "Direct Followers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Following",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "RelatedExpenses",
               "label": "Aggregated Expenses",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Expense",
               "sourceFieldName": null
            },
            {
               "name": "Followers",
               "label": "Followers",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "ProjectCustomers",
               "label": "Project Customers",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Customer",
               "sourceFieldName": null
            },
            {
               "name": "TeamMembers",
               "label": "Work Item Team Members",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "WorkItemTeamLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "AttachedPosts",
               "label": "V5 Posts",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Post",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "AttachedNotes",
               "label": "Notes",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Note",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "AttachedEmails",
               "label": "Emails",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Email",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "RelatedTimesheetEntries",
               "label": "Time Entries",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Timesheet",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Expenses",
               "label": "Expenses",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Expense",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "OriginatedIssues",
               "label": "Originated Cases",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "OriginatedFrom"
            },
            {
               "name": "Issues",
               "label": "Cases",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "Case",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Resources",
               "label": "Resources",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RegularResourceLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Reviewers",
               "label": "Reviewers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ReviewerLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Managers",
               "label": "Managers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ManagerResourceLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Discussions",
               "label": "Discussions",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "",
               "relatedTypeName": "DiscussionPost",
               "sourceFieldName": "Entity"
            },
            {
               "name": "LikedBy",
               "label": "Liked By",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Like",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "AllTeamMembers",
               "label": "All Team Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "AllManagers",
               "label": "All Managers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "AllReviewers",
               "label": "All Reviewers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "AllResources",
               "label": "All Resources",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "Successors",
               "label": "Successors",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "DependencyLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Predecessors",
               "label": "Predecessors",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "DependencyLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "DependsOn"
            },
            {
               "name": "AllTeam",
               "label": "Team Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ResourceLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Documents",
               "label": "Files",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "WorkItemAttachmentLink",
               "relatedTypeName": "Document",
               "sourceFieldName": "Entity"
            },
            {
               "name": "UsersOpenedStopwatches",
               "label": "Active Stopwatch Users",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "Stopwatch",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Topics",
               "label": "Topics",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "TopicWorkItemLink",
               "relatedTypeName": "Topic",
               "sourceFieldName": "Entity"
            },
            {
               "name": "DataObjects",
               "label": "DataObjects",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "SourceObject"
            },
            {
               "name": "RelatedIssues",
               "label": "Issues",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "Issue",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "RelatedRisks",
               "label": "Risks",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "Risk",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "RelatedBugs",
               "label": "Bugs",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "Bug",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "RelatedRequests",
               "label": "Requests",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "EnhancementRequest",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "PermisionDefinitions",
               "label": "Permission Definitions",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Permission",
               "relatedTypeName": "ResourceEntity",
               "sourceFieldName": "Entity"
            },
            {
               "name": "AdditionalObjectProperties",
               "label": "Overview",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "AdditionalObjectProperties",
               "sourceFieldName": "RelatedItem"
            },
            {
               "name": "R_ProjectCost",
               "label": "ProjectCost",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "C_ProjectCosts"
            },
            {
               "name": "R_ActionItemsFor",
               "label": "Action Items",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "GenericTask",
               "sourceFieldName": "C_ActionItemsfor"
            }
         ]
      },
      {
         "typeName": "GenericTask",
         "relations": [
            {
               "name": "Groups",
               "label": "Groups",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupTaskLink",
               "relatedTypeName": "Group",
               "sourceFieldName": "Entity"
            },
            {
               "name": "AllImpacting",
               "label": "Impacting and Sub Items",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "WorkItemHierarchyLink",
               "relatedTypeName": "GenericTask",
               "sourceFieldName": "Parent"
            },
            {
               "name": "Children",
               "label": "Sub Items",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "RealWorkItemHierarchyLink",
               "relatedTypeName": "GenericTask",
               "sourceFieldName": "Parent"
            },
            {
               "name": "Shortcuts",
               "label": "Shortcuts",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "ShortcutLink",
               "relatedTypeName": "GenericTask",
               "sourceFieldName": "Parent"
            },
            {
               "name": "Impacting",
               "label": "Impacting",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ProgressImpactLink",
               "relatedTypeName": "GenericTask",
               "sourceFieldName": "Parent"
            },
            {
               "name": "R_TaskFinancials",
               "label": "Monthly Task Breakdown",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "C_ParentTask"
            },
            {
               "name": "AllImpacted",
               "label": "Impacted and Parents",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "WorkItemHierarchyLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Child"
            },
            {
               "name": "WhereUsedAsShortcut",
               "label": "Shortcut in",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "ShortcutLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Child"
            },
            {
               "name": "ImpactedBy",
               "label": "Impacted By",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "ProgressImpactLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Child"
            },
            {
               "name": "DirectFollowers",
               "label": "Direct Followers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Following",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "RelatedExpenses",
               "label": "Aggregated Expenses",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Expense",
               "sourceFieldName": null
            },
            {
               "name": "Followers",
               "label": "Followers",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "ProjectCustomers",
               "label": "Project Customers",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Customer",
               "sourceFieldName": null
            },
            {
               "name": "TeamMembers",
               "label": "Work Item Team Members",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "WorkItemTeamLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "AttachedPosts",
               "label": "V5 Posts",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Post",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "AttachedNotes",
               "label": "Notes",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Note",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "AttachedEmails",
               "label": "Emails",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Email",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "RelatedTimesheetEntries",
               "label": "Time Entries",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Timesheet",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Expenses",
               "label": "Expenses",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Expense",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "OriginatedIssues",
               "label": "Originated Cases",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "OriginatedFrom"
            },
            {
               "name": "Issues",
               "label": "Cases",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "Case",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Resources",
               "label": "Resources",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RegularResourceLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Reviewers",
               "label": "Reviewers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ReviewerLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Managers",
               "label": "Managers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ManagerResourceLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Discussions",
               "label": "Discussions",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "",
               "relatedTypeName": "DiscussionPost",
               "sourceFieldName": "Entity"
            },
            {
               "name": "LikedBy",
               "label": "Liked By",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Like",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "AllTeamMembers",
               "label": "All Team Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "AllManagers",
               "label": "All Managers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "AllReviewers",
               "label": "All Reviewers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "AllResources",
               "label": "All Resources",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "Successors",
               "label": "Successors",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "DependencyLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Predecessors",
               "label": "Predecessors",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "DependencyLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "DependsOn"
            },
            {
               "name": "AllTeam",
               "label": "Team Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ResourceLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Documents",
               "label": "Files",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "WorkItemAttachmentLink",
               "relatedTypeName": "Document",
               "sourceFieldName": "Entity"
            },
            {
               "name": "UsersOpenedStopwatches",
               "label": "Active Stopwatch Users",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "Stopwatch",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Topics",
               "label": "Topics",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "TopicWorkItemLink",
               "relatedTypeName": "Topic",
               "sourceFieldName": "Entity"
            },
            {
               "name": "DataObjects",
               "label": "DataObjects",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "SourceObject"
            },
            {
               "name": "RelatedIssues",
               "label": "Issues",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "Issue",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "RelatedRisks",
               "label": "Risks",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "Risk",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "RelatedBugs",
               "label": "Bugs",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "Bug",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "RelatedRequests",
               "label": "Requests",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "EnhancementRequest",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "PermisionDefinitions",
               "label": "Permission Definitions",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Permission",
               "relatedTypeName": "ResourceEntity",
               "sourceFieldName": "Entity"
            },
            {
               "name": "AdditionalObjectProperties",
               "label": "Overview",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "AdditionalObjectProperties",
               "sourceFieldName": "RelatedItem"
            },
            {
               "name": "R_ProjectCost",
               "label": "ProjectCost",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "C_ProjectCosts"
            },
            {
               "name": "R_ActionItemsFor",
               "label": "Action Items",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "GenericTask",
               "sourceFieldName": "C_ActionItemsfor"
            },
            {
               "name": "DirectLaborResources",
               "label": "Labor Resources",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "LaborResourceLinkDirect",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "DirectNonLaborResources",
               "label": "Non-Labor Resources",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "NonLaborResourceLinkDirect",
               "relatedTypeName": "NonLaborResource",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "FinancialResources",
               "label": "Financial Resources",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ResourceLinkFinancial",
               "relatedTypeName": "GenericResourceEntity",
               "sourceFieldName": "WorkItem"
            }
         ]
      },
      {
         "typeName": "PlanningComponent",
         "relations": [
            {
               "name": "AllImpacted",
               "label": "Impacted and Parents",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "WorkItemHierarchyLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Child"
            },
            {
               "name": "WhereUsedAsShortcut",
               "label": "Shortcut in",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "ShortcutLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Child"
            },
            {
               "name": "ImpactedBy",
               "label": "Impacted By",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "ProgressImpactLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Child"
            },
            {
               "name": "DirectFollowers",
               "label": "Direct Followers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Following",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "RelatedExpenses",
               "label": "Aggregated Expenses",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Expense",
               "sourceFieldName": null
            },
            {
               "name": "Followers",
               "label": "Followers",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "ProjectCustomers",
               "label": "Project Customers",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Customer",
               "sourceFieldName": null
            },
            {
               "name": "TeamMembers",
               "label": "Work Item Team Members",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "WorkItemTeamLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "AttachedPosts",
               "label": "V5 Posts",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Post",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "AttachedNotes",
               "label": "Notes",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Note",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "AttachedEmails",
               "label": "Emails",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Email",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "RelatedTimesheetEntries",
               "label": "Time Entries",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Timesheet",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Expenses",
               "label": "Expenses",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Expense",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "OriginatedIssues",
               "label": "Originated Cases",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "OriginatedFrom"
            },
            {
               "name": "Issues",
               "label": "Cases",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "Case",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Resources",
               "label": "Resources",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RegularResourceLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Reviewers",
               "label": "Reviewers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ReviewerLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Managers",
               "label": "Managers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ManagerResourceLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Discussions",
               "label": "Discussions",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "",
               "relatedTypeName": "DiscussionPost",
               "sourceFieldName": "Entity"
            },
            {
               "name": "LikedBy",
               "label": "Liked By",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Like",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "AllTeamMembers",
               "label": "All Team Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "AllManagers",
               "label": "All Managers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "AllReviewers",
               "label": "All Reviewers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "AllResources",
               "label": "All Resources",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "Successors",
               "label": "Successors",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "DependencyLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Predecessors",
               "label": "Predecessors",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "DependencyLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "DependsOn"
            },
            {
               "name": "AllTeam",
               "label": "Team Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ResourceLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Documents",
               "label": "Files",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "WorkItemAttachmentLink",
               "relatedTypeName": "Document",
               "sourceFieldName": "Entity"
            },
            {
               "name": "UsersOpenedStopwatches",
               "label": "Active Stopwatch Users",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "Stopwatch",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Topics",
               "label": "Topics",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "TopicWorkItemLink",
               "relatedTypeName": "Topic",
               "sourceFieldName": "Entity"
            },
            {
               "name": "DataObjects",
               "label": "DataObjects",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "SourceObject"
            },
            {
               "name": "RelatedIssues",
               "label": "Issues",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "Issue",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "RelatedRisks",
               "label": "Risks",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "Risk",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "RelatedBugs",
               "label": "Bugs",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "Bug",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "RelatedRequests",
               "label": "Requests",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "EnhancementRequest",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "PermisionDefinitions",
               "label": "Permission Definitions",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Permission",
               "relatedTypeName": "ResourceEntity",
               "sourceFieldName": "Entity"
            },
            {
               "name": "AdditionalObjectProperties",
               "label": "Overview",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "AdditionalObjectProperties",
               "sourceFieldName": "RelatedItem"
            },
            {
               "name": "R_ProjectCost",
               "label": "ProjectCost",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "C_ProjectCosts"
            },
            {
               "name": "R_ActionItemsFor",
               "label": "Action Items",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "GenericTask",
               "sourceFieldName": "C_ActionItemsfor"
            },
            {
               "name": "AllImpacting",
               "label": "Impacting and Sub Items",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "WorkItemHierarchyLink",
               "relatedTypeName": "PlanningComponent",
               "sourceFieldName": "Parent"
            },
            {
               "name": "Tasks",
               "label": "Tasks",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "GenericTask",
               "sourceFieldName": "Milestone"
            },
            {
               "name": "Children",
               "label": "Sub Items",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "RealWorkItemHierarchyLink",
               "relatedTypeName": "GenericTask",
               "sourceFieldName": "Parent"
            },
            {
               "name": "Shortcuts",
               "label": "Shortcuts",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "ShortcutLink",
               "relatedTypeName": "PlanningComponent",
               "sourceFieldName": "Parent"
            },
            {
               "name": "Impacting",
               "label": "Impacting",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ProgressImpactLink",
               "relatedTypeName": "PlanningComponent",
               "sourceFieldName": "Parent"
            },
            {
               "name": "DirectNonLaborResources",
               "label": "Non-Labor Resources",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "NonLaborResourceLinkDirect",
               "relatedTypeName": "NonLaborResource",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "AggregatedNonLaborResources",
               "label": "Work Item's aggregated Non-Labor Resources",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "NonLaborResourceLinkAggregated",
               "relatedTypeName": "NonLaborResource",
               "sourceFieldName": null
            },
            {
               "name": "Groups",
               "label": "Groups",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupTaskLink",
               "relatedTypeName": "Group",
               "sourceFieldName": "Entity"
            },
            {
               "name": "R_TaskFinancials",
               "label": "Monthly Task Breakdown",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "C_ParentTask"
            },
            {
               "name": "DirectLaborResources",
               "label": "Work Item's direct Labor Resources",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "LaborResourceLinkDirect",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "FinancialResources",
               "label": "Financial Resources",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ResourceLinkFinancial",
               "relatedTypeName": "GenericResourceEntity",
               "sourceFieldName": "WorkItem"
            }
         ]
      },
      {
         "typeName": "Project",
         "relations": [
            {
               "name": "AllImpacting",
               "label": "Impacting and Sub Items",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "WorkItemHierarchyLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Parent"
            },
            {
               "name": "AllImpacted",
               "label": "Impacted and Parents",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "WorkItemHierarchyLink",
               "relatedTypeName": "GenericProject",
               "sourceFieldName": "Child"
            },
            {
               "name": "AllTeam",
               "label": "Team Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ResourceLink",
               "relatedTypeName": "ResourceEntity",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Customers",
               "label": "Customers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "CustomerLink",
               "relatedTypeName": "Customer",
               "sourceFieldName": "Entity"
            },
            {
               "name": "ExpenseSheets",
               "label": "Expense Sheets",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "ExpenseSheet",
               "sourceFieldName": "Project"
            },
            {
               "name": "Children",
               "label": "Sub Items",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "RealWorkItemHierarchyLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Parent"
            },
            {
               "name": "Shortcuts",
               "label": "Shortcuts",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "ShortcutLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Parent"
            },
            {
               "name": "Impacting",
               "label": "Impacting",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ProgressImpactLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Parent"
            },
            {
               "name": "ImpactedBy",
               "label": "Impacted By",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "ProgressImpactLink",
               "relatedTypeName": "GenericProject",
               "sourceFieldName": "Child"
            },
            {
               "name": "DirectLaborResources",
               "label": "Labor Resources",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "LaborResourceLinkDirect",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "FinancialResources",
               "label": "Financial Resources",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ResourceLinkFinancial",
               "relatedTypeName": "GenericResourceEntity",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "AllFiles",
               "label": "Files (Aggregated)",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Document",
               "sourceFieldName": null
            },
            {
               "name": "AllRisks",
               "label": "Risks (Aggregated)",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Risk",
               "sourceFieldName": null
            },
            {
               "name": "AllIssues",
               "label": "Issues (Aggregated)",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Issue",
               "sourceFieldName": null
            },
            {
               "name": "AllRequests",
               "label": "Requests (Aggregated)",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "EnhancementRequest",
               "sourceFieldName": null
            },
            {
               "name": "AllBugs",
               "label": "Bugs (Aggregated)",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Bug",
               "sourceFieldName": null
            },
            {
               "name": "AllCases",
               "label": "Cases (Aggregated)",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": null
            },
            {
               "name": "WhereUsedAsShortcut",
               "label": "Shortcut in",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "ShortcutLink",
               "relatedTypeName": "Project",
               "sourceFieldName": "Child"
            },
            {
               "name": "R_ProjFinancials",
               "label": "Monthly Task Breakdown",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "C_ParentProject"
            },
            {
               "name": "R_CreativeWorkload",
               "label": "Creative Workload",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "C_CreativeWorkload"
            },
            {
               "name": "R_ResourcingDetails",
               "label": "Resourcing Details",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Project",
               "sourceFieldName": "C_ResourcingDetails"
            },
            {
               "name": "R_RetainerDrawDownProject",
               "label": "Retainer Draw Down Project",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Project",
               "sourceFieldName": "C_RetainerPlaceholderProject"
            },
            {
               "name": "R_TempReviewers",
               "label": "Temp Reviewers",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "ReviewerLink",
               "relatedTypeName": "ReviewerLink",
               "sourceFieldName": "C_ProjectRef"
            },
            {
               "name": "AllWorkItems",
               "label": "All Work Items",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "WorkItem",
               "sourceFieldName": null
            },
            {
               "name": "AllWorkItemsWithShortcuts",
               "label": "All Work Items With Shortcuts",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "WorkItem",
               "sourceFieldName": null
            },
            {
               "name": "WorkItems",
               "label": "Work Items",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "PlanningComponent",
               "sourceFieldName": "Project"
            },
            {
               "name": "Timesheets",
               "label": "Aggregated Time Entries",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Timesheet",
               "sourceFieldName": "Project"
            },
            {
               "name": "TargetedIssues",
               "label": "Targeted Cases",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "PlannedFor"
            },
            {
               "name": "JobTitles",
               "label": "Job Titles",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "JobTitleRateLink",
               "relatedTypeName": "JobTitle",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Groups",
               "label": "Groups",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupProjectLink",
               "relatedTypeName": "Group",
               "sourceFieldName": "Entity"
            },
            {
               "name": "DirectNonLaborResources",
               "label": "Non-Labor Resources",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "NonLaborResourceLinkDirect",
               "relatedTypeName": "NonLaborResource",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "AggregatedNonLaborResources",
               "label": "Aggregated Non-Labor Resources",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "NonLaborResourceLinkAggregated",
               "relatedTypeName": "NonLaborResource",
               "sourceFieldName": null
            },
            {
               "name": "AggregatedLaborResources",
               "label": "Aggregated Labor Resources",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "LaborResourceLinkAggregated",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "DirectFollowers",
               "label": "Direct Followers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Following",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "RelatedExpenses",
               "label": "Aggregated Expenses",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Expense",
               "sourceFieldName": null
            },
            {
               "name": "Followers",
               "label": "Followers",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "ProjectCustomers",
               "label": "Project Customers",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Customer",
               "sourceFieldName": null
            },
            {
               "name": "TeamMembers",
               "label": "Work Item Team Members",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "WorkItemTeamLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "AttachedPosts",
               "label": "V5 Posts",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Post",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "AttachedNotes",
               "label": "Notes",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Note",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "AttachedEmails",
               "label": "Emails",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Email",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "RelatedTimesheetEntries",
               "label": "Time Entries",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Timesheet",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Expenses",
               "label": "Expenses",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Expense",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "OriginatedIssues",
               "label": "Originated Cases",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "OriginatedFrom"
            },
            {
               "name": "Issues",
               "label": "Cases",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "Case",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Resources",
               "label": "Resources",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RegularResourceLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Reviewers",
               "label": "Reviewers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ReviewerLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Managers",
               "label": "Managers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ManagerResourceLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Discussions",
               "label": "Discussions",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "",
               "relatedTypeName": "DiscussionPost",
               "sourceFieldName": "Entity"
            },
            {
               "name": "LikedBy",
               "label": "Liked By",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Like",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "AllTeamMembers",
               "label": "All Team Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "AllManagers",
               "label": "All Managers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "AllReviewers",
               "label": "All Reviewers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "AllResources",
               "label": "All Resources",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "Successors",
               "label": "Successors",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "DependencyLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Predecessors",
               "label": "Predecessors",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "DependencyLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "DependsOn"
            },
            {
               "name": "Documents",
               "label": "Files",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "WorkItemAttachmentLink",
               "relatedTypeName": "Document",
               "sourceFieldName": "Entity"
            },
            {
               "name": "UsersOpenedStopwatches",
               "label": "Active Stopwatch Users",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "Stopwatch",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Topics",
               "label": "Topics",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "TopicWorkItemLink",
               "relatedTypeName": "Topic",
               "sourceFieldName": "Entity"
            },
            {
               "name": "DataObjects",
               "label": "DataObjects",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "SourceObject"
            },
            {
               "name": "RelatedIssues",
               "label": "Issues",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "Issue",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "RelatedRisks",
               "label": "Risks",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "Risk",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "RelatedBugs",
               "label": "Bugs",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "Bug",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "RelatedRequests",
               "label": "Requests",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "EnhancementRequest",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "PermisionDefinitions",
               "label": "Permission Definitions",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Permission",
               "relatedTypeName": "ResourceEntity",
               "sourceFieldName": "Entity"
            },
            {
               "name": "AdditionalObjectProperties",
               "label": "Overview",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "AdditionalObjectProperties",
               "sourceFieldName": "RelatedItem"
            },
            {
               "name": "R_ProjectCost",
               "label": "ProjectCost",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "C_ProjectCosts"
            },
            {
               "name": "R_ActionItemsFor",
               "label": "Action Items",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "GenericTask",
               "sourceFieldName": "C_ActionItemsfor"
            }
         ]
      },
      {
         "typeName": "Program",
         "relations": [
            {
               "name": "AllFiles",
               "label": "Files (Aggregated)",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Document",
               "sourceFieldName": null
            },
            {
               "name": "AllImpacting",
               "label": "Impacting and Sub Items",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "WorkItemHierarchyLink",
               "relatedTypeName": "Project",
               "sourceFieldName": "Parent"
            },
            {
               "name": "Children",
               "label": "Sub Items",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "RealWorkItemHierarchyLink",
               "relatedTypeName": "Project",
               "sourceFieldName": "Parent"
            },
            {
               "name": "Impacting",
               "label": "Impacting",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ProgressImpactLink",
               "relatedTypeName": "Project",
               "sourceFieldName": "Parent"
            },
            {
               "name": "AllRisks",
               "label": "Risks (Aggregated)",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Risk",
               "sourceFieldName": null
            },
            {
               "name": "AllIssues",
               "label": "Issues (Aggregated)",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Issue",
               "sourceFieldName": null
            },
            {
               "name": "AllRequests",
               "label": "Requests (Aggregated)",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "EnhancementRequest",
               "sourceFieldName": null
            },
            {
               "name": "AllBugs",
               "label": "Bugs (Aggregated)",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Bug",
               "sourceFieldName": null
            },
            {
               "name": "AllCases",
               "label": "Cases (Aggregated)",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": null
            },
            {
               "name": "AllWorkItems",
               "label": "All Work Items",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "WorkItem",
               "sourceFieldName": null
            },
            {
               "name": "AllWorkItemsWithShortcuts",
               "label": "All Work Items With Shortcuts",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "WorkItem",
               "sourceFieldName": null
            },
            {
               "name": "WorkItems",
               "label": "Work Items",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "PlanningComponent",
               "sourceFieldName": "Project"
            },
            {
               "name": "Timesheets",
               "label": "Aggregated Time Entries",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Timesheet",
               "sourceFieldName": "Project"
            },
            {
               "name": "TargetedIssues",
               "label": "Targeted Cases",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "PlannedFor"
            },
            {
               "name": "JobTitles",
               "label": "Job Titles",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "JobTitleRateLink",
               "relatedTypeName": "JobTitle",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Groups",
               "label": "Groups",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupProjectLink",
               "relatedTypeName": "Group",
               "sourceFieldName": "Entity"
            },
            {
               "name": "DirectNonLaborResources",
               "label": "Non-Labor Resources",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "NonLaborResourceLinkDirect",
               "relatedTypeName": "NonLaborResource",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "AggregatedNonLaborResources",
               "label": "Aggregated Non-Labor Resources",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "NonLaborResourceLinkAggregated",
               "relatedTypeName": "NonLaborResource",
               "sourceFieldName": null
            },
            {
               "name": "AggregatedLaborResources",
               "label": "Aggregated Labor Resources",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "LaborResourceLinkAggregated",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "DirectFollowers",
               "label": "Direct Followers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Following",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "RelatedExpenses",
               "label": "Aggregated Expenses",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Expense",
               "sourceFieldName": null
            },
            {
               "name": "Followers",
               "label": "Followers",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "ProjectCustomers",
               "label": "Project Customers",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Customer",
               "sourceFieldName": null
            },
            {
               "name": "TeamMembers",
               "label": "Work Item Team Members",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "WorkItemTeamLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "AttachedPosts",
               "label": "V5 Posts",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Post",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "AttachedNotes",
               "label": "Notes",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Note",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "AttachedEmails",
               "label": "Emails",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Email",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "RelatedTimesheetEntries",
               "label": "Time Entries",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Timesheet",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Expenses",
               "label": "Expenses",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Expense",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "OriginatedIssues",
               "label": "Originated Cases",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "OriginatedFrom"
            },
            {
               "name": "Issues",
               "label": "Cases",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "Case",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Resources",
               "label": "Resources",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RegularResourceLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Reviewers",
               "label": "Reviewers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ReviewerLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Managers",
               "label": "Managers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ManagerResourceLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Discussions",
               "label": "Discussions",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "",
               "relatedTypeName": "DiscussionPost",
               "sourceFieldName": "Entity"
            },
            {
               "name": "LikedBy",
               "label": "Liked By",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Like",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "AllTeamMembers",
               "label": "All Team Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "AllManagers",
               "label": "All Managers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "AllReviewers",
               "label": "All Reviewers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "AllResources",
               "label": "All Resources",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "Successors",
               "label": "Successors",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "DependencyLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Predecessors",
               "label": "Predecessors",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "DependencyLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "DependsOn"
            },
            {
               "name": "AllTeam",
               "label": "Team Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ResourceLink",
               "relatedTypeName": "ResourceEntity",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Documents",
               "label": "Files",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "WorkItemAttachmentLink",
               "relatedTypeName": "Document",
               "sourceFieldName": "Entity"
            },
            {
               "name": "UsersOpenedStopwatches",
               "label": "Active Stopwatch Users",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "Stopwatch",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Topics",
               "label": "Topics",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "TopicWorkItemLink",
               "relatedTypeName": "Topic",
               "sourceFieldName": "Entity"
            },
            {
               "name": "DataObjects",
               "label": "DataObjects",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "SourceObject"
            },
            {
               "name": "RelatedIssues",
               "label": "Issues",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "Issue",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "RelatedRisks",
               "label": "Risks",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "Risk",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "RelatedBugs",
               "label": "Bugs",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "Bug",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "RelatedRequests",
               "label": "Requests",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "EnhancementRequest",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "PermisionDefinitions",
               "label": "Permission Definitions",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Permission",
               "relatedTypeName": "ResourceEntity",
               "sourceFieldName": "Entity"
            },
            {
               "name": "AdditionalObjectProperties",
               "label": "Overview",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "AdditionalObjectProperties",
               "sourceFieldName": "RelatedItem"
            },
            {
               "name": "R_ProjectCost",
               "label": "ProjectCost",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "C_ProjectCosts"
            },
            {
               "name": "R_ActionItemsFor",
               "label": "Action Items",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "GenericTask",
               "sourceFieldName": "C_ActionItemsfor"
            }
         ]
      },
      {
         "typeName": "GenericProject",
         "relations": [
            {
               "name": "AllWorkItems",
               "label": "All Work Items",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "WorkItem",
               "sourceFieldName": null
            },
            {
               "name": "AllWorkItemsWithShortcuts",
               "label": "All Work Items With Shortcuts",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "WorkItem",
               "sourceFieldName": null
            },
            {
               "name": "WorkItems",
               "label": "Work Items",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "PlanningComponent",
               "sourceFieldName": "Project"
            },
            {
               "name": "Timesheets",
               "label": "Aggregated Time Entries",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Timesheet",
               "sourceFieldName": "Project"
            },
            {
               "name": "TargetedIssues",
               "label": "Targeted Cases",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "PlannedFor"
            },
            {
               "name": "JobTitles",
               "label": "Job Titles",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "JobTitleRateLink",
               "relatedTypeName": "JobTitle",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Groups",
               "label": "Groups",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupProjectLink",
               "relatedTypeName": "Group",
               "sourceFieldName": "Entity"
            },
            {
               "name": "DirectNonLaborResources",
               "label": "Non-Labor Resources",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "NonLaborResourceLinkDirect",
               "relatedTypeName": "NonLaborResource",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "AggregatedNonLaborResources",
               "label": "Aggregated Non-Labor Resources",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "NonLaborResourceLinkAggregated",
               "relatedTypeName": "NonLaborResource",
               "sourceFieldName": null
            },
            {
               "name": "AggregatedLaborResources",
               "label": "Aggregated Labor Resources",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "LaborResourceLinkAggregated",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "DirectFollowers",
               "label": "Direct Followers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Following",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "RelatedExpenses",
               "label": "Aggregated Expenses",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Expense",
               "sourceFieldName": null
            },
            {
               "name": "Followers",
               "label": "Followers",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "ProjectCustomers",
               "label": "Project Customers",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Customer",
               "sourceFieldName": null
            },
            {
               "name": "TeamMembers",
               "label": "Work Item Team Members",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "WorkItemTeamLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "AttachedPosts",
               "label": "V5 Posts",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Post",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "AttachedNotes",
               "label": "Notes",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Note",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "AttachedEmails",
               "label": "Emails",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Email",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "RelatedTimesheetEntries",
               "label": "Time Entries",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Timesheet",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Expenses",
               "label": "Expenses",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Expense",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "OriginatedIssues",
               "label": "Originated Cases",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "OriginatedFrom"
            },
            {
               "name": "Issues",
               "label": "Cases",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "Case",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Resources",
               "label": "Resources",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RegularResourceLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Reviewers",
               "label": "Reviewers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ReviewerLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Managers",
               "label": "Managers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ManagerResourceLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Discussions",
               "label": "Discussions",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "",
               "relatedTypeName": "DiscussionPost",
               "sourceFieldName": "Entity"
            },
            {
               "name": "LikedBy",
               "label": "Liked By",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Like",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "AllTeamMembers",
               "label": "All Team Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "AllManagers",
               "label": "All Managers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "AllReviewers",
               "label": "All Reviewers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "AllResources",
               "label": "All Resources",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "Successors",
               "label": "Successors",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "DependencyLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Predecessors",
               "label": "Predecessors",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "DependencyLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "DependsOn"
            },
            {
               "name": "AllTeam",
               "label": "Team Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ResourceLink",
               "relatedTypeName": "ResourceEntity",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Documents",
               "label": "Files",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "WorkItemAttachmentLink",
               "relatedTypeName": "Document",
               "sourceFieldName": "Entity"
            },
            {
               "name": "UsersOpenedStopwatches",
               "label": "Active Stopwatch Users",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "Stopwatch",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Topics",
               "label": "Topics",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "TopicWorkItemLink",
               "relatedTypeName": "Topic",
               "sourceFieldName": "Entity"
            },
            {
               "name": "DataObjects",
               "label": "DataObjects",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "SourceObject"
            },
            {
               "name": "RelatedIssues",
               "label": "Issues",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "Issue",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "RelatedRisks",
               "label": "Risks",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "Risk",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "RelatedBugs",
               "label": "Bugs",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "Bug",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "RelatedRequests",
               "label": "Requests",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "EnhancementRequest",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "PermisionDefinitions",
               "label": "Permission Definitions",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Permission",
               "relatedTypeName": "ResourceEntity",
               "sourceFieldName": "Entity"
            },
            {
               "name": "AdditionalObjectProperties",
               "label": "Overview",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "AdditionalObjectProperties",
               "sourceFieldName": "RelatedItem"
            },
            {
               "name": "R_ProjectCost",
               "label": "ProjectCost",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "C_ProjectCosts"
            },
            {
               "name": "R_ActionItemsFor",
               "label": "Action Items",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "GenericTask",
               "sourceFieldName": "C_ActionItemsfor"
            },
            {
               "name": "AllImpacting",
               "label": "Impacting and Sub Items",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "WorkItemHierarchyLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Parent"
            },
            {
               "name": "AllImpacted",
               "label": "Impacted and Parents",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "WorkItemHierarchyLink",
               "relatedTypeName": "GenericProject",
               "sourceFieldName": "Child"
            },
            {
               "name": "Customers",
               "label": "Customers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "CustomerLink",
               "relatedTypeName": "Customer",
               "sourceFieldName": "Entity"
            },
            {
               "name": "ExpenseSheets",
               "label": "Expense Sheets",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "ExpenseSheet",
               "sourceFieldName": "Project"
            },
            {
               "name": "Children",
               "label": "Sub Items",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "RealWorkItemHierarchyLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Parent"
            },
            {
               "name": "Shortcuts",
               "label": "Shortcuts",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "ShortcutLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Parent"
            },
            {
               "name": "Impacting",
               "label": "Impacting",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ProgressImpactLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Parent"
            },
            {
               "name": "ImpactedBy",
               "label": "Impacted By",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "ProgressImpactLink",
               "relatedTypeName": "GenericProject",
               "sourceFieldName": "Child"
            },
            {
               "name": "DirectLaborResources",
               "label": "Labor Resources",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "LaborResourceLinkDirect",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "FinancialResources",
               "label": "Financial Resources",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ResourceLinkFinancial",
               "relatedTypeName": "GenericResourceEntity",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "AllFiles",
               "label": "Files (Aggregated)",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Document",
               "sourceFieldName": null
            },
            {
               "name": "AllRisks",
               "label": "Risks (Aggregated)",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Risk",
               "sourceFieldName": null
            },
            {
               "name": "AllIssues",
               "label": "Issues (Aggregated)",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Issue",
               "sourceFieldName": null
            },
            {
               "name": "AllRequests",
               "label": "Requests (Aggregated)",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "EnhancementRequest",
               "sourceFieldName": null
            },
            {
               "name": "AllBugs",
               "label": "Bugs (Aggregated)",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Bug",
               "sourceFieldName": null
            },
            {
               "name": "AllCases",
               "label": "Cases (Aggregated)",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": null
            },
            {
               "name": "WhereUsedAsShortcut",
               "label": "Shortcut in",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "ShortcutLink",
               "relatedTypeName": "Project",
               "sourceFieldName": "Child"
            },
            {
               "name": "R_ProjFinancials",
               "label": "Monthly Task Breakdown",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "C_ParentProject"
            },
            {
               "name": "R_CreativeWorkload",
               "label": "Creative Workload",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "C_CreativeWorkload"
            },
            {
               "name": "R_ResourcingDetails",
               "label": "Resourcing Details",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Project",
               "sourceFieldName": "C_ResourcingDetails"
            },
            {
               "name": "R_RetainerDrawDownProject",
               "label": "Retainer Draw Down Project",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Project",
               "sourceFieldName": "C_RetainerPlaceholderProject"
            },
            {
               "name": "R_TempReviewers",
               "label": "Temp Reviewers",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "ReviewerLink",
               "relatedTypeName": "ReviewerLink",
               "sourceFieldName": "C_ProjectRef"
            }
         ]
      },
      {
         "typeName": "WorkItem",
         "relations": [
            {
               "name": "DirectFollowers",
               "label": "Direct Followers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Following",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "RelatedExpenses",
               "label": "Aggregated Expenses",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Expense",
               "sourceFieldName": null
            },
            {
               "name": "Followers",
               "label": "Followers",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "ProjectCustomers",
               "label": "Project Customers",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Customer",
               "sourceFieldName": null
            },
            {
               "name": "TeamMembers",
               "label": "Work Item Team Members",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "WorkItemTeamLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "AttachedPosts",
               "label": "V5 Posts",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Post",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "AttachedNotes",
               "label": "Notes",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Note",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "AttachedEmails",
               "label": "Emails",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Email",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "RelatedTimesheetEntries",
               "label": "Time Entries",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Timesheet",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Expenses",
               "label": "Expenses",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Expense",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "OriginatedIssues",
               "label": "Originated Cases",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "OriginatedFrom"
            },
            {
               "name": "Issues",
               "label": "Cases",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "Case",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Resources",
               "label": "Resources",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RegularResourceLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Reviewers",
               "label": "Reviewers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ReviewerLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Managers",
               "label": "Managers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ManagerResourceLink",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Discussions",
               "label": "Discussions",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "",
               "relatedTypeName": "DiscussionPost",
               "sourceFieldName": "Entity"
            },
            {
               "name": "LikedBy",
               "label": "Liked By",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Like",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "AllTeamMembers",
               "label": "All Team Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "AllManagers",
               "label": "All Managers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "AllReviewers",
               "label": "All Reviewers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "AllResources",
               "label": "All Resources",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "Successors",
               "label": "Successors",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "DependencyLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Predecessors",
               "label": "Predecessors",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "DependencyLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "DependsOn"
            },
            {
               "name": "AllTeam",
               "label": "Team Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ResourceLink",
               "relatedTypeName": "ResourceEntity",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Documents",
               "label": "Files",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "WorkItemAttachmentLink",
               "relatedTypeName": "Document",
               "sourceFieldName": "Entity"
            },
            {
               "name": "UsersOpenedStopwatches",
               "label": "Active Stopwatch Users",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "Stopwatch",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Topics",
               "label": "Topics",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "TopicWorkItemLink",
               "relatedTypeName": "Topic",
               "sourceFieldName": "Entity"
            },
            {
               "name": "DataObjects",
               "label": "DataObjects",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "SourceObject"
            },
            {
               "name": "RelatedIssues",
               "label": "Issues",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "Issue",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "RelatedRisks",
               "label": "Risks",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "Risk",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "RelatedBugs",
               "label": "Bugs",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "Bug",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "RelatedRequests",
               "label": "Requests",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "EnhancementRequest",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Groups",
               "label": "Groups",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "",
               "relatedTypeName": "Group",
               "sourceFieldName": "Entity"
            },
            {
               "name": "PermisionDefinitions",
               "label": "Permission Definitions",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Permission",
               "relatedTypeName": "ResourceEntity",
               "sourceFieldName": "Entity"
            },
            {
               "name": "AdditionalObjectProperties",
               "label": "Overview",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "AdditionalObjectProperties",
               "sourceFieldName": "RelatedItem"
            },
            {
               "name": "R_ProjectCost",
               "label": "ProjectCost",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "C_ProjectCosts"
            },
            {
               "name": "R_ActionItemsFor",
               "label": "Action Items",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "GenericTask",
               "sourceFieldName": "C_ActionItemsfor"
            },
            {
               "name": "AllImpacted",
               "label": "Impacted and Parents",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "WorkItemHierarchyLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Child"
            },
            {
               "name": "WhereUsedAsShortcut",
               "label": "Shortcut in",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "ShortcutLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Child"
            },
            {
               "name": "ImpactedBy",
               "label": "Impacted By",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "ProgressImpactLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Child"
            },
            {
               "name": "AllImpacting",
               "label": "Impacting and Sub Items",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "WorkItemHierarchyLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Parent"
            },
            {
               "name": "Tasks",
               "label": "Tasks",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "GenericTask",
               "sourceFieldName": "Milestone"
            },
            {
               "name": "Children",
               "label": "Sub Items",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "RealWorkItemHierarchyLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Parent"
            },
            {
               "name": "Shortcuts",
               "label": "Shortcuts",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "ShortcutLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Parent"
            },
            {
               "name": "Impacting",
               "label": "Impacting",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ProgressImpactLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Parent"
            },
            {
               "name": "DirectNonLaborResources",
               "label": "Non-Labor Resources",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "NonLaborResourceLinkDirect",
               "relatedTypeName": "NonLaborResource",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "AggregatedNonLaborResources",
               "label": "Aggregated Non-Labor Resources",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "NonLaborResourceLinkAggregated",
               "relatedTypeName": "NonLaborResource",
               "sourceFieldName": null
            },
            {
               "name": "R_TaskFinancials",
               "label": "Monthly Task Breakdown",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "C_ParentTask"
            },
            {
               "name": "DirectLaborResources",
               "label": "Labor Resources",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "LaborResourceLinkDirect",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "FinancialResources",
               "label": "Financial Resources",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ResourceLinkFinancial",
               "relatedTypeName": "GenericResourceEntity",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "AllWorkItems",
               "label": "All Work Items",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "WorkItem",
               "sourceFieldName": null
            },
            {
               "name": "AllWorkItemsWithShortcuts",
               "label": "All Work Items With Shortcuts",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "WorkItem",
               "sourceFieldName": null
            },
            {
               "name": "WorkItems",
               "label": "Work Items",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "PlanningComponent",
               "sourceFieldName": "Project"
            },
            {
               "name": "Timesheets",
               "label": "Aggregated Time Entries",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Timesheet",
               "sourceFieldName": "Project"
            },
            {
               "name": "TargetedIssues",
               "label": "Targeted Cases",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": "PlannedFor"
            },
            {
               "name": "JobTitles",
               "label": "Job Titles",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "JobTitleRateLink",
               "relatedTypeName": "JobTitle",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "AggregatedLaborResources",
               "label": "Aggregated Labor Resources",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "LaborResourceLinkAggregated",
               "relatedTypeName": "User",
               "sourceFieldName": "WorkItem"
            },
            {
               "name": "Customers",
               "label": "Customers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "CustomerLink",
               "relatedTypeName": "Customer",
               "sourceFieldName": "Entity"
            },
            {
               "name": "ExpenseSheets",
               "label": "Expense Sheets",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "ExpenseSheet",
               "sourceFieldName": "Project"
            },
            {
               "name": "AllFiles",
               "label": "Files (Aggregated)",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Document",
               "sourceFieldName": null
            },
            {
               "name": "AllRisks",
               "label": "Risks (Aggregated)",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Risk",
               "sourceFieldName": null
            },
            {
               "name": "AllIssues",
               "label": "Issues (Aggregated)",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Issue",
               "sourceFieldName": null
            },
            {
               "name": "AllRequests",
               "label": "Requests (Aggregated)",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "EnhancementRequest",
               "sourceFieldName": null
            },
            {
               "name": "AllBugs",
               "label": "Bugs (Aggregated)",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Bug",
               "sourceFieldName": null
            },
            {
               "name": "AllCases",
               "label": "Cases (Aggregated)",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Case",
               "sourceFieldName": null
            },
            {
               "name": "R_ProjFinancials",
               "label": "Monthly Task Breakdown",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "C_ParentProject"
            },
            {
               "name": "R_CreativeWorkload",
               "label": "Creative Workload",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "C_CreativeWorkload"
            },
            {
               "name": "R_ResourcingDetails",
               "label": "Resourcing Details",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Project",
               "sourceFieldName": "C_ResourcingDetails"
            },
            {
               "name": "R_RetainerDrawDownProject",
               "label": "Retainer Draw Down Project",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Project",
               "sourceFieldName": "C_RetainerPlaceholderProject"
            },
            {
               "name": "R_TempReviewers",
               "label": "Temp Reviewers",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "ReviewerLink",
               "relatedTypeName": "ReviewerLink",
               "sourceFieldName": "C_ProjectRef"
            }
         ]
      },
      {
         "typeName": "Topic",
         "relations": [
            {
               "name": "DirectFollowers",
               "label": "Direct Followers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Following",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Discussions",
               "label": "Discussions",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "",
               "relatedTypeName": "DiscussionPost",
               "sourceFieldName": "Entity"
            },
            {
               "name": "WorkItems",
               "label": "Work Items",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "TopicWorkItemLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Topic"
            },
            {
               "name": "LikedBy",
               "label": "Liked By",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Like",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Followers",
               "label": "Followers",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "Cases",
               "label": "Cases",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "TopicCaseLink",
               "relatedTypeName": "Case",
               "sourceFieldName": "Topic"
            },
            {
               "name": "Customers",
               "label": "Customers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "TopicCustomerLink",
               "relatedTypeName": "Customer",
               "sourceFieldName": "Topic"
            },
            {
               "name": "ExpenseSheets",
               "label": "Expense Sheets",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "TopicExpenseSheetLink",
               "relatedTypeName": "ExpenseSheet",
               "sourceFieldName": "Topic"
            },
            {
               "name": "ExpenseEntries",
               "label": "Expense Entries",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "TopicExpenseEntryLink",
               "relatedTypeName": "Expense",
               "sourceFieldName": "Topic"
            },
            {
               "name": "Groups",
               "label": "Groups",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "TopicGroupLink",
               "relatedTypeName": "Group",
               "sourceFieldName": "Topic"
            },
            {
               "name": "Documents",
               "label": "Files",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "TopicDocumentLink",
               "relatedTypeName": "Document",
               "sourceFieldName": "Topic"
            },
            {
               "name": "DataObjects",
               "label": "DataObjects",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "SourceObject"
            }
         ]
      },
      {
         "typeName": "Following",
         "relations": []
      },
      {
         "typeName": "Like",
         "relations": []
      },
      {
         "typeName": "NLRDiscussionLink",
         "relations": []
      },
      {
         "typeName": "ReportDiscussionLink",
         "relations": []
      },
      {
         "typeName": "UserReportDiscussionLink",
         "relations": []
      },
      {
         "typeName": "SystemReportDiscussionLink",
         "relations": []
      },
      {
         "typeName": "ExpenseEntryDiscussionLink",
         "relations": []
      },
      {
         "typeName": "ExpenseSheetDiscussionLink",
         "relations": []
      },
      {
         "typeName": "CustomerDiscussionLink",
         "relations": []
      },
      {
         "typeName": "CaseDiscussionLink",
         "relations": []
      },
      {
         "typeName": "WorkItemDiscussionLink",
         "relations": []
      },
      {
         "typeName": "DiscussionLink",
         "relations": []
      },
      {
         "typeName": "DiscussionReply",
         "relations": [
            {
               "name": "Documents",
               "label": "Files",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "DiscussionMessageAttachmentLink",
               "relatedTypeName": "Document",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Lines",
               "label": "Lines",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "String",
               "sourceFieldName": null
            },
            {
               "name": "WorkItems",
               "label": "Work Items",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "WorkItemDiscussionLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "DiscussionMessage"
            },
            {
               "name": "Cases",
               "label": "Cases",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "CaseDiscussionLink",
               "relatedTypeName": "Case",
               "sourceFieldName": "DiscussionMessage"
            },
            {
               "name": "Customers",
               "label": "Customers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "CustomerDiscussionLink",
               "relatedTypeName": "Customer",
               "sourceFieldName": "DiscussionMessage"
            },
            {
               "name": "ExpenseSheets",
               "label": "Expense Sheets",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ExpenseSheetDiscussionLink",
               "relatedTypeName": "ExpenseSheet",
               "sourceFieldName": "DiscussionMessage"
            },
            {
               "name": "ExpenseEntries",
               "label": "Expense Entries",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ExpenseEntryDiscussionLink",
               "relatedTypeName": "Expense",
               "sourceFieldName": "DiscussionMessage"
            },
            {
               "name": "Reports",
               "label": "Related Reports",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "ReportDiscussionLink",
               "relatedTypeName": "FoldersAndReports",
               "sourceFieldName": "DiscussionMessage"
            },
            {
               "name": "LikedBy",
               "label": "Liked By",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Like",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "NonLaborResource",
               "label": "Non-Labor Resource",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "NLRDiscussionLink",
               "relatedTypeName": "NonLaborResource",
               "sourceFieldName": "DiscussionMessage"
            }
         ]
      },
      {
         "typeName": "DiscussionPost",
         "relations": [
            {
               "name": "Replies",
               "label": "Replies",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "DiscussionReply",
               "sourceFieldName": "Post"
            },
            {
               "name": "Topics",
               "label": "Topics",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "TopicDiscussionLink",
               "relatedTypeName": "Topic",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Documents",
               "label": "Files",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "DiscussionMessageAttachmentLink",
               "relatedTypeName": "Document",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Lines",
               "label": "Lines",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "String",
               "sourceFieldName": null
            },
            {
               "name": "WorkItems",
               "label": "Work Items",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "WorkItemDiscussionLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "DiscussionMessage"
            },
            {
               "name": "Cases",
               "label": "Cases",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "CaseDiscussionLink",
               "relatedTypeName": "Case",
               "sourceFieldName": "DiscussionMessage"
            },
            {
               "name": "Customers",
               "label": "Customers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "CustomerDiscussionLink",
               "relatedTypeName": "Customer",
               "sourceFieldName": "DiscussionMessage"
            },
            {
               "name": "ExpenseSheets",
               "label": "Expense Sheets",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ExpenseSheetDiscussionLink",
               "relatedTypeName": "ExpenseSheet",
               "sourceFieldName": "DiscussionMessage"
            },
            {
               "name": "ExpenseEntries",
               "label": "Expense Entries",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ExpenseEntryDiscussionLink",
               "relatedTypeName": "Expense",
               "sourceFieldName": "DiscussionMessage"
            },
            {
               "name": "Reports",
               "label": "Related Reports",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "ReportDiscussionLink",
               "relatedTypeName": "FoldersAndReports",
               "sourceFieldName": "DiscussionMessage"
            },
            {
               "name": "LikedBy",
               "label": "Liked By",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Like",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "NonLaborResource",
               "label": "Non-Labor Resource",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "NLRDiscussionLink",
               "relatedTypeName": "NonLaborResource",
               "sourceFieldName": "DiscussionMessage"
            }
         ]
      },
      {
         "typeName": "DiscussionMessage",
         "relations": [
            {
               "name": "Documents",
               "label": "Files",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "DiscussionMessageAttachmentLink",
               "relatedTypeName": "Document",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Lines",
               "label": "Lines",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "String",
               "sourceFieldName": null
            },
            {
               "name": "WorkItems",
               "label": "Work Items",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "WorkItemDiscussionLink",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "DiscussionMessage"
            },
            {
               "name": "Cases",
               "label": "Cases",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "CaseDiscussionLink",
               "relatedTypeName": "Case",
               "sourceFieldName": "DiscussionMessage"
            },
            {
               "name": "Customers",
               "label": "Customers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "CustomerDiscussionLink",
               "relatedTypeName": "Customer",
               "sourceFieldName": "DiscussionMessage"
            },
            {
               "name": "ExpenseSheets",
               "label": "Expense Sheets",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ExpenseSheetDiscussionLink",
               "relatedTypeName": "ExpenseSheet",
               "sourceFieldName": "DiscussionMessage"
            },
            {
               "name": "ExpenseEntries",
               "label": "Expense Entries",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ExpenseEntryDiscussionLink",
               "relatedTypeName": "Expense",
               "sourceFieldName": "DiscussionMessage"
            },
            {
               "name": "Reports",
               "label": "Related Reports",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "ReportDiscussionLink",
               "relatedTypeName": "FoldersAndReports",
               "sourceFieldName": "DiscussionMessage"
            },
            {
               "name": "LikedBy",
               "label": "Liked By",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Like",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "NonLaborResource",
               "label": "Non-Labor Resource",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "NLRDiscussionLink",
               "relatedTypeName": "NonLaborResource",
               "sourceFieldName": "DiscussionMessage"
            },
            {
               "name": "Replies",
               "label": "Replies",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "DiscussionReply",
               "sourceFieldName": "Post"
            },
            {
               "name": "Topics",
               "label": "Topics",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "TopicDiscussionLink",
               "relatedTypeName": "Topic",
               "sourceFieldName": "Entity"
            }
         ]
      },
      {
         "typeName": "GroupTaskLink",
         "relations": []
      },
      {
         "typeName": "GroupProjectLink",
         "relations": []
      },
      {
         "typeName": "GroupCaseLink",
         "relations": []
      },
      {
         "typeName": "GroupCustomerLink",
         "relations": []
      },
      {
         "typeName": "GroupLink",
         "relations": []
      },
      {
         "typeName": "RecycleBinItems",
         "relations": []
      },
      {
         "typeName": "Stopwatch",
         "relations": []
      },
      {
         "typeName": "ProfileLink",
         "relations": []
      },
      {
         "typeName": "SubGroupHierarchyLink",
         "relations": []
      },
      {
         "typeName": "GroupMembershipLink",
         "relations": []
      },
      {
         "typeName": "GroupHierarchyLink",
         "relations": []
      },
      {
         "typeName": "SkillLink",
         "relations": []
      },
      {
         "typeName": "MembershipLink",
         "relations": []
      },
      {
         "typeName": "NLRAttachmentLink",
         "relations": []
      },
      {
         "typeName": "WorkItemAttachmentLink",
         "relations": []
      },
      {
         "typeName": "DashboardAttachmentLink",
         "relations": []
      },
      {
         "typeName": "ReportAttachmentLink",
         "relations": []
      },
      {
         "typeName": "UserAttachmentLink",
         "relations": []
      },
      {
         "typeName": "ExpenseSheetAttachmentLink",
         "relations": []
      },
      {
         "typeName": "CustomerAttachmentLink",
         "relations": []
      },
      {
         "typeName": "DiscussionMessageAttachmentLink",
         "relations": []
      },
      {
         "typeName": "ResourceGroupEntityAttachmentLink",
         "relations": []
      },
      {
         "typeName": "IssueAttachmentLink",
         "relations": []
      },
      {
         "typeName": "ExpenseEntryAttachmentLink",
         "relations": []
      },
      {
         "typeName": "AttachmentLink",
         "relations": []
      },
      {
         "typeName": "AdditionalManagerLink",
         "relations": []
      },
      {
         "typeName": "OwnerLink",
         "relations": []
      },
      {
         "typeName": "ManagerResourceLink",
         "relations": []
      },
      {
         "typeName": "RegularResourceLink",
         "relations": [
            {
               "name": "TimesheetsAssignedToResource",
               "label": "Timesheets Assigned to Resource",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Timesheet",
               "sourceFieldName": "HumanResource"
            },
            {
               "name": "R_Tasks",
               "label": "Tasks",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RegularResourceLink",
               "relatedTypeName": "RegularResourceLink",
               "sourceFieldName": "C_ProjectResLink"
            }
         ]
      },
      {
         "typeName": "ReviewerLink",
         "relations": []
      },
      {
         "typeName": "WorkItemTeamLink",
         "relations": [
            {
               "name": "TimesheetsAssignedToResource",
               "label": "Timesheets Assigned to Resource",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Timesheet",
               "sourceFieldName": "HumanResource"
            },
            {
               "name": "R_Tasks",
               "label": "Tasks",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RegularResourceLink",
               "relatedTypeName": "RegularResourceLink",
               "sourceFieldName": "C_ProjectResLink"
            }
         ]
      },
      {
         "typeName": "JobTitleRateLink",
         "relations": []
      },
      {
         "typeName": "ResourceLink",
         "relations": [
            {
               "name": "TimesheetsAssignedToResource",
               "label": "Timesheets Assigned to Resource",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Timesheet",
               "sourceFieldName": "HumanResource"
            },
            {
               "name": "R_Tasks",
               "label": "Tasks",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RegularResourceLink",
               "relatedTypeName": "RegularResourceLink",
               "sourceFieldName": "C_ProjectResLink"
            }
         ]
      },
      {
         "typeName": "ProgressImpactLink",
         "relations": []
      },
      {
         "typeName": "RealWorkItemHierarchyLink",
         "relations": []
      },
      {
         "typeName": "ShortcutLink",
         "relations": []
      },
      {
         "typeName": "BaseWorkItemHierarchyLink",
         "relations": []
      },
      {
         "typeName": "WorkItemHierarchyLink",
         "relations": []
      },
      {
         "typeName": "SchedulingType",
         "relations": []
      },
      {
         "typeName": "CurrencyType",
         "relations": []
      },
      {
         "typeName": "TrackStatus",
         "relations": []
      },
      {
         "typeName": "TemplateItemType",
         "relations": []
      },
      {
         "typeName": "LaborBudgetPickup",
         "relations": []
      },
      {
         "typeName": "ExpenseType",
         "relations": []
      },
      {
         "typeName": "NonLaborResourceLinkCategory",
         "relations": []
      },
      {
         "typeName": "ReportingPeriodPickup",
         "relations": []
      },
      {
         "typeName": "GeographicalRegion",
         "relations": []
      },
      {
         "typeName": "ResourceUtilizationCategory",
         "relations": []
      },
      {
         "typeName": "InvestmentType",
         "relations": []
      },
      {
         "typeName": "PackagedObjectCategory",
         "relations": []
      },
      {
         "typeName": "NotifyUsers",
         "relations": []
      },
      {
         "typeName": "EditorsMode",
         "relations": []
      },
      {
         "typeName": "ManagerRole",
         "relations": []
      },
      {
         "typeName": "NumericFormat",
         "relations": []
      },
      {
         "typeName": "DashboardStatus",
         "relations": []
      },
      {
         "typeName": "UserShortcut",
         "relations": []
      },
      {
         "typeName": "IntegrationAuthenticationType",
         "relations": []
      },
      {
         "typeName": "AuthorizationGroup",
         "relations": []
      },
      {
         "typeName": "CustomIcon",
         "relations": []
      },
      {
         "typeName": "ProofAlert",
         "relations": []
      },
      {
         "typeName": "ProofRole",
         "relations": []
      },
      {
         "typeName": "TriggeredBy",
         "relations": []
      },
      {
         "typeName": "SyncStatus",
         "relations": []
      },
      {
         "typeName": "ReplyMarkedType",
         "relations": []
      },
      {
         "typeName": "CompanySize",
         "relations": []
      },
      {
         "typeName": "CustomerSuccessStatus",
         "relations": []
      },
      {
         "typeName": "Tier",
         "relations": []
      },
      {
         "typeName": "AccountStatus",
         "relations": []
      },
      {
         "typeName": "LicenseType",
         "relations": []
      },
      {
         "typeName": "StorageType",
         "relations": []
      },
      {
         "typeName": "ShortDateFormat",
         "relations": []
      },
      {
         "typeName": "ProjectSize",
         "relations": []
      },
      {
         "typeName": "PostState",
         "relations": []
      },
      {
         "typeName": "PostType",
         "relations": []
      },
      {
         "typeName": "DiscussionEmailNotifications",
         "relations": []
      },
      {
         "typeName": "CompletenessRole",
         "relations": []
      },
      {
         "typeName": "SpecialRole",
         "relations": []
      },
      {
         "typeName": "FileType",
         "relations": []
      },
      {
         "typeName": "WidgetType",
         "relations": []
      },
      {
         "typeName": "CreatorType",
         "relations": []
      },
      {
         "typeName": "StopwatchAggregateState",
         "relations": []
      },
      {
         "typeName": "CommentType",
         "relations": []
      },
      {
         "typeName": "StopwatchState",
         "relations": []
      },
      {
         "typeName": "MilestoneType",
         "relations": []
      },
      {
         "typeName": "Region",
         "relations": []
      },
      {
         "typeName": "Package",
         "relations": []
      },
      {
         "typeName": "CaseBusinessImpact",
         "relations": []
      },
      {
         "typeName": "State",
         "relations": []
      },
      {
         "typeName": "TaskReportingPolicy",
         "relations": []
      },
      {
         "typeName": "CaseState",
         "relations": []
      },
      {
         "typeName": "ChargedType",
         "relations": []
      },
      {
         "typeName": "RequestType",
         "relations": []
      },
      {
         "typeName": "RiskImpact",
         "relations": []
      },
      {
         "typeName": "RisksRate",
         "relations": []
      },
      {
         "typeName": "BusinessImpact",
         "relations": []
      },
      {
         "typeName": "ExceptionType",
         "relations": []
      },
      {
         "typeName": "ObjectAccessType",
         "relations": []
      },
      {
         "typeName": "Months",
         "relations": []
      },
      {
         "typeName": "WeekDays",
         "relations": []
      },
      {
         "typeName": "RiskState",
         "relations": []
      },
      {
         "typeName": "DependencyType",
         "relations": []
      },
      {
         "typeName": "Pending",
         "relations": []
      },
      {
         "typeName": "Severity",
         "relations": []
      },
      {
         "typeName": "ExpenseCategory",
         "relations": []
      },
      {
         "typeName": "WorkPolicy",
         "relations": []
      },
      {
         "typeName": "DocumentType",
         "relations": []
      },
      {
         "typeName": "RecipientType",
         "relations": []
      },
      {
         "typeName": "TaskType",
         "relations": []
      },
      {
         "typeName": "RateType",
         "relations": []
      },
      {
         "typeName": "ResourceRole",
         "relations": []
      },
      {
         "typeName": "Importance",
         "relations": []
      },
      {
         "typeName": "Language",
         "relations": []
      },
      {
         "typeName": "RecurrenceType",
         "relations": []
      },
      {
         "typeName": "CommitLevel",
         "relations": []
      },
      {
         "typeName": "CountryState",
         "relations": []
      },
      {
         "typeName": "ReportExtensionType",
         "relations": []
      },
      {
         "typeName": "BudgetStatus",
         "relations": []
      },
      {
         "typeName": "Countries",
         "relations": []
      },
      {
         "typeName": "ImportedFrom",
         "relations": []
      },
      {
         "typeName": "TimeZone",
         "relations": []
      },
      {
         "typeName": "Widget",
         "relations": []
      },
      {
         "typeName": "CaseCustomerLink",
         "relations": []
      },
      {
         "typeName": "IssueTeamMembers",
         "relations": []
      },
      {
         "typeName": "RelatedWork",
         "relations": []
      },
      {
         "typeName": "EnhancementRequest",
         "relations": [
            {
               "name": "R_tageConversationHistory",
               "label": "Records - % Conversion History",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "C_ProbabilityofConversionHistory"
            },
            {
               "name": "DirectFollowers",
               "label": "Direct Followers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Following",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Groups",
               "label": "Groups",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCaseLink",
               "relatedTypeName": "Group",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Documents",
               "label": "Files",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "IssueAttachmentLink",
               "relatedTypeName": "Document",
               "sourceFieldName": "Entity"
            },
            {
               "name": "AttachedPosts",
               "label": "V5 Posts",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Post",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "AttachedNotes",
               "label": "Notes",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Note",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "AttachedEmails",
               "label": "Emails",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Email",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "Customers",
               "label": "Customers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "CaseCustomerLink",
               "relatedTypeName": "Customer",
               "sourceFieldName": "Entity"
            },
            {
               "name": "AllTeamMembers",
               "label": "Team And Subscribers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "WorkItems",
               "label": "Work Items",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Case"
            },
            {
               "name": "Team",
               "label": "Team Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "IssueTeamMembers",
               "relatedTypeName": "User",
               "sourceFieldName": "Case"
            },
            {
               "name": "LikedBy",
               "label": "Liked By",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Like",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Followers",
               "label": "Followers",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "Discussions",
               "label": "Discussions",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "",
               "relatedTypeName": "DiscussionPost",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Topics",
               "label": "Topics",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "TopicCaseLink",
               "relatedTypeName": "Topic",
               "sourceFieldName": "Entity"
            },
            {
               "name": "DataObjects",
               "label": "DataObjects",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "SourceObject"
            },
            {
               "name": "PermisionDefinitions",
               "label": "Permission Definitions",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Permission",
               "relatedTypeName": "ResourceEntity",
               "sourceFieldName": "Entity"
            },
            {
               "name": "AdditionalObjectProperties",
               "label": "Overview",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "AdditionalObjectProperties",
               "sourceFieldName": "RelatedItem"
            }
         ]
      },
      {
         "typeName": "Bug",
         "relations": [
            {
               "name": "DirectFollowers",
               "label": "Direct Followers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Following",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Groups",
               "label": "Groups",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCaseLink",
               "relatedTypeName": "Group",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Documents",
               "label": "Files",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "IssueAttachmentLink",
               "relatedTypeName": "Document",
               "sourceFieldName": "Entity"
            },
            {
               "name": "AttachedPosts",
               "label": "V5 Posts",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Post",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "AttachedNotes",
               "label": "Notes",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Note",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "AttachedEmails",
               "label": "Emails",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Email",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "Customers",
               "label": "Customers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "CaseCustomerLink",
               "relatedTypeName": "Customer",
               "sourceFieldName": "Entity"
            },
            {
               "name": "AllTeamMembers",
               "label": "Team And Subscribers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "WorkItems",
               "label": "Work Items",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Case"
            },
            {
               "name": "Team",
               "label": "Team Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "IssueTeamMembers",
               "relatedTypeName": "User",
               "sourceFieldName": "Case"
            },
            {
               "name": "LikedBy",
               "label": "Liked By",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Like",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Followers",
               "label": "Followers",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "Discussions",
               "label": "Discussions",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "",
               "relatedTypeName": "DiscussionPost",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Topics",
               "label": "Topics",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "TopicCaseLink",
               "relatedTypeName": "Topic",
               "sourceFieldName": "Entity"
            },
            {
               "name": "DataObjects",
               "label": "DataObjects",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "SourceObject"
            },
            {
               "name": "PermisionDefinitions",
               "label": "Permission Definitions",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Permission",
               "relatedTypeName": "ResourceEntity",
               "sourceFieldName": "Entity"
            },
            {
               "name": "AdditionalObjectProperties",
               "label": "Overview",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "AdditionalObjectProperties",
               "sourceFieldName": "RelatedItem"
            }
         ]
      },
      {
         "typeName": "Risk",
         "relations": [
            {
               "name": "DirectFollowers",
               "label": "Direct Followers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Following",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Groups",
               "label": "Groups",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCaseLink",
               "relatedTypeName": "Group",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Documents",
               "label": "Files",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "IssueAttachmentLink",
               "relatedTypeName": "Document",
               "sourceFieldName": "Entity"
            },
            {
               "name": "AttachedPosts",
               "label": "V5 Posts",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Post",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "AttachedNotes",
               "label": "Notes",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Note",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "AttachedEmails",
               "label": "Emails",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Email",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "Customers",
               "label": "Customers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "CaseCustomerLink",
               "relatedTypeName": "Customer",
               "sourceFieldName": "Entity"
            },
            {
               "name": "AllTeamMembers",
               "label": "Team And Subscribers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "WorkItems",
               "label": "Work Items",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Case"
            },
            {
               "name": "Team",
               "label": "Team Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "IssueTeamMembers",
               "relatedTypeName": "User",
               "sourceFieldName": "Case"
            },
            {
               "name": "LikedBy",
               "label": "Liked By",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Like",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Followers",
               "label": "Followers",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "Discussions",
               "label": "Discussions",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "",
               "relatedTypeName": "DiscussionPost",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Topics",
               "label": "Topics",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "TopicCaseLink",
               "relatedTypeName": "Topic",
               "sourceFieldName": "Entity"
            },
            {
               "name": "DataObjects",
               "label": "DataObjects",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "SourceObject"
            },
            {
               "name": "PermisionDefinitions",
               "label": "Permission Definitions",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Permission",
               "relatedTypeName": "ResourceEntity",
               "sourceFieldName": "Entity"
            },
            {
               "name": "AdditionalObjectProperties",
               "label": "Overview",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "AdditionalObjectProperties",
               "sourceFieldName": "RelatedItem"
            }
         ]
      },
      {
         "typeName": "Issue",
         "relations": [
            {
               "name": "DirectFollowers",
               "label": "Direct Followers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Following",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Groups",
               "label": "Groups",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCaseLink",
               "relatedTypeName": "Group",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Documents",
               "label": "Files",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "IssueAttachmentLink",
               "relatedTypeName": "Document",
               "sourceFieldName": "Entity"
            },
            {
               "name": "AttachedPosts",
               "label": "V5 Posts",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Post",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "AttachedNotes",
               "label": "Notes",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Note",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "AttachedEmails",
               "label": "Emails",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Email",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "Customers",
               "label": "Customers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "CaseCustomerLink",
               "relatedTypeName": "Customer",
               "sourceFieldName": "Entity"
            },
            {
               "name": "AllTeamMembers",
               "label": "Team And Subscribers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "WorkItems",
               "label": "Work Items",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Case"
            },
            {
               "name": "Team",
               "label": "Team Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "IssueTeamMembers",
               "relatedTypeName": "User",
               "sourceFieldName": "Case"
            },
            {
               "name": "LikedBy",
               "label": "Liked By",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Like",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Followers",
               "label": "Followers",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "Discussions",
               "label": "Discussions",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "",
               "relatedTypeName": "DiscussionPost",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Topics",
               "label": "Topics",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "TopicCaseLink",
               "relatedTypeName": "Topic",
               "sourceFieldName": "Entity"
            },
            {
               "name": "DataObjects",
               "label": "DataObjects",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "SourceObject"
            },
            {
               "name": "PermisionDefinitions",
               "label": "Permission Definitions",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Permission",
               "relatedTypeName": "ResourceEntity",
               "sourceFieldName": "Entity"
            },
            {
               "name": "AdditionalObjectProperties",
               "label": "Overview",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "AdditionalObjectProperties",
               "sourceFieldName": "RelatedItem"
            }
         ]
      },
      {
         "typeName": "Case",
         "relations": [
            {
               "name": "DirectFollowers",
               "label": "Direct Followers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Following",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Groups",
               "label": "Groups",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCaseLink",
               "relatedTypeName": "Group",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Documents",
               "label": "Files",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "IssueAttachmentLink",
               "relatedTypeName": "Document",
               "sourceFieldName": "Entity"
            },
            {
               "name": "AttachedPosts",
               "label": "V5 Posts",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Post",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "AttachedNotes",
               "label": "Notes",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Note",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "AttachedEmails",
               "label": "Emails",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Email",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "Customers",
               "label": "Customers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "CaseCustomerLink",
               "relatedTypeName": "Customer",
               "sourceFieldName": "Entity"
            },
            {
               "name": "AllTeamMembers",
               "label": "Team And Subscribers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "WorkItems",
               "label": "Work Items",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "RelatedWork",
               "relatedTypeName": "WorkItem",
               "sourceFieldName": "Case"
            },
            {
               "name": "Team",
               "label": "Team Members",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "IssueTeamMembers",
               "relatedTypeName": "User",
               "sourceFieldName": "Case"
            },
            {
               "name": "LikedBy",
               "label": "Liked By",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Like",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Followers",
               "label": "Followers",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "Discussions",
               "label": "Discussions",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "",
               "relatedTypeName": "DiscussionPost",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Topics",
               "label": "Topics",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "TopicCaseLink",
               "relatedTypeName": "Topic",
               "sourceFieldName": "Entity"
            },
            {
               "name": "DataObjects",
               "label": "DataObjects",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "SourceObject"
            },
            {
               "name": "PermisionDefinitions",
               "label": "Permission Definitions",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Permission",
               "relatedTypeName": "ResourceEntity",
               "sourceFieldName": "Entity"
            },
            {
               "name": "AdditionalObjectProperties",
               "label": "Overview",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "AdditionalObjectProperties",
               "sourceFieldName": "RelatedItem"
            },
            {
               "name": "R_tageConversationHistory",
               "label": "Records - % Conversion History",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "C_ProbabilityofConversionHistory"
            }
         ]
      },
      {
         "typeName": "Expense",
         "relations": [
            {
               "name": "DirectFollowers",
               "label": "Direct Followers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Following",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Documents",
               "label": "Files",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ExpenseEntryAttachmentLink",
               "relatedTypeName": "Document",
               "sourceFieldName": "Entity"
            },
            {
               "name": "LikedBy",
               "label": "Liked By",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Like",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Followers",
               "label": "Followers",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "Discussions",
               "label": "Discussions",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "",
               "relatedTypeName": "DiscussionPost",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Topics",
               "label": "Topics",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "TopicExpenseEntryLink",
               "relatedTypeName": "Topic",
               "sourceFieldName": "Entity"
            },
            {
               "name": "DataObjects",
               "label": "DataObjects",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "SourceObject"
            }
         ]
      },
      {
         "typeName": "ExpenseSheet",
         "relations": [
            {
               "name": "DirectFollowers",
               "label": "Direct Followers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Following",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Documents",
               "label": "Files",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "ExpenseSheetAttachmentLink",
               "relatedTypeName": "Document",
               "sourceFieldName": "Entity"
            },
            {
               "name": "AttachedPosts",
               "label": "V5 Posts",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "Post",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "LikedBy",
               "label": "Liked By",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Like",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Followers",
               "label": "Followers",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "Expenses",
               "label": "Expenses",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Expense",
               "sourceFieldName": "ExpenseSheet"
            },
            {
               "name": "Discussions",
               "label": "Discussions",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "",
               "relatedTypeName": "DiscussionPost",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Topics",
               "label": "Topics",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "TopicExpenseSheetLink",
               "relatedTypeName": "Topic",
               "sourceFieldName": "Entity"
            },
            {
               "name": "DataObjects",
               "label": "DataObjects",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "SourceObject"
            }
         ]
      },
      {
         "typeName": "CurrencyExchangeRate",
         "relations": []
      },
      {
         "typeName": "EmailRecipient",
         "relations": []
      },
      {
         "typeName": "CustomerLink",
         "relations": []
      },
      {
         "typeName": "ContactPerson",
         "relations": [
            {
               "name": "RecipientOfEmails",
               "label": "Recipient Of Emails",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "EmailRecipient",
               "sourceFieldName": "Recipient"
            }
         ]
      },
      {
         "typeName": "Customer",
         "relations": [
            {
               "name": "DirectFollowers",
               "label": "Direct Followers",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Following",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "AttachedEmails",
               "label": "Emails",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Email",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "AttachedNotes",
               "label": "Notes",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Note",
               "sourceFieldName": "AttachedTo"
            },
            {
               "name": "Documents",
               "label": "Files",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "CustomerAttachmentLink",
               "relatedTypeName": "Document",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Groups",
               "label": "Groups",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "GroupCustomerLink",
               "relatedTypeName": "Group",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Projects",
               "label": "Projects",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "CustomerLink",
               "relatedTypeName": "Project",
               "sourceFieldName": "Customer"
            },
            {
               "name": "Issues",
               "label": "Cases",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "CaseCustomerLink",
               "relatedTypeName": "Case",
               "sourceFieldName": "Customer"
            },
            {
               "name": "LikedBy",
               "label": "Liked By",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Like",
               "relatedTypeName": "User",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Followers",
               "label": "Followers",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "Contacts",
               "label": "Contacts",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "ContactPerson",
               "sourceFieldName": "Customer"
            },
            {
               "name": "Discussions",
               "label": "Discussions",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": "",
               "relatedTypeName": "DiscussionPost",
               "sourceFieldName": "Entity"
            },
            {
               "name": "Topics",
               "label": "Topics",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "TopicCustomerLink",
               "relatedTypeName": "Topic",
               "sourceFieldName": "Entity"
            },
            {
               "name": "DataObjects",
               "label": "DataObjects",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "SourceObject"
            },
            {
               "name": "PermisionDefinitions",
               "label": "Permission Definitions",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "Permission",
               "relatedTypeName": "ResourceEntity",
               "sourceFieldName": "Entity"
            },
            {
               "name": "AdditionalObjectProperties",
               "label": "Overview",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "AdditionalObjectProperties",
               "sourceFieldName": "RelatedItem"
            },
            {
               "name": "R_ReportedActualRevenue",
               "label": "Reported Actual Revenue",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "C_ReportedActualRevenue"
            },
            {
               "name": "R_CustomerRequests",
               "label": "Requests",
               "roleLabel": "",
               "readOnly": true,
               "linkTypeName": null,
               "relatedTypeName": "EnhancementRequest",
               "sourceFieldName": "C_BBHCustomer"
            },
            {
               "name": "R_CustomerRateCard",
               "label": "Customer Rate Card",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": "TopicLink",
               "relatedTypeName": "TopicLink",
               "sourceFieldName": "C_CustomerRateCard"
            },
            {
               "name": "R_Dashboards",
               "label": "Dashboards",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Dashboard",
               "sourceFieldName": "C_BBHCustomer"
            },
            {
               "name": "R_ReportedRevenue",
               "label": "Reported Revenue",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "Data",
               "sourceFieldName": "C_ReportedRevenue"
            }
         ]
      },
      {
         "typeName": "Rate",
         "relations": []
      },
      {
         "typeName": "Timesheet",
         "relations": []
      },
      {
         "typeName": "Organization",
         "relations": [
            {
               "name": "AllUsers",
               "label": "All Users",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "User",
               "sourceFieldName": null
            },
            {
               "name": "ErrorNotifications",
               "label": "Error Notifications",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "ResourceEntity",
               "sourceFieldName": null
            },
            {
               "name": "R_MonthCount",
               "label": "Months",
               "roleLabel": "",
               "readOnly": false,
               "linkTypeName": null,
               "relatedTypeName": "C_OrganizationCopyofMonths",
               "sourceFieldName": null
            }
         ]
      },
      {
         "typeName": "ProjectType",
         "relations": []
      },
      {
         "typeName": "Phase",
         "relations": []
      },
      {
         "typeName": "Role",
         "relations": []
      },
      {
         "typeName": "Industry",
         "relations": []
      },
      {
         "typeName": "DataObjectType",
         "relations": []
      },
      {
         "typeName": "C_EnhancementRequestSPRINT",
         "relations": []
      },
      {
         "typeName": "C_EnhancementRequestScopeReference",
         "relations": []
      },
      {
         "typeName": "C_EnhancementRequestContractwithlegalentity",
         "relations": []
      },
      {
         "typeName": "C_EnhancementRequestIndustry",
         "relations": []
      },
      {
         "typeName": "C_EnhancementRequestGeographicalScope",
         "relations": []
      },
      {
         "typeName": "C_EnhancementRequestOffices",
         "relations": []
      },
      {
         "typeName": "C_EnhancementRequestTypeofOpportunity",
         "relations": []
      },
      {
         "typeName": "C_EnhancementRequestProjectorAOR",
         "relations": []
      },
      {
         "typeName": "C_EnhancementRequestProactiveorReactive",
         "relations": []
      },
      {
         "typeName": "C_EnhancementRequestNextAction",
         "relations": []
      },
      {
         "typeName": "C_EnhancementRequestProjectStage",
         "relations": []
      },
      {
         "typeName": "C_EnhancementRequestDiscipline",
         "relations": []
      },
      {
         "typeName": "C_EnhancementRequestTypeofRelationship",
         "relations": []
      },
      {
         "typeName": "C_EnhancementRequestCreatedbyRegion",
         "relations": []
      },
      {
         "typeName": "C_UserBBHRegion",
         "relations": []
      },
      {
         "typeName": "C_EnhancementRequestProjectType",
         "relations": []
      },
      {
         "typeName": "C_CustomerCreatedbyWhichRegion",
         "relations": []
      },
      {
         "typeName": "C_EnhancementRequestApproveReject",
         "relations": []
      },
      {
         "typeName": "C_CustomerContractwithwhichlegalentity",
         "relations": []
      },
      {
         "typeName": "C_EnhancementRequestProbabilityofConversion",
         "relations": []
      },
      {
         "typeName": "C_DataRoleRateYear",
         "relations": []
      },
      {
         "typeName": "C_UserDiscipline",
         "relations": []
      },
      {
         "typeName": "C_UserBBHDepartment",
         "relations": []
      },
      {
         "typeName": "C_DataCostType",
         "relations": []
      },
      {
         "typeName": "C_EnhancementRequestHowmanycompetingagencies",
         "relations": []
      },
      {
         "typeName": "C_CustomerTypeofRelationship",
         "relations": []
      },
      {
         "typeName": "C_DataDiscipline",
         "relations": []
      },
      {
         "typeName": "C_ProjectResourcing",
         "relations": []
      },
      {
         "typeName": "C_ProjectProjectStage",
         "relations": []
      },
      {
         "typeName": "C_ProjectTypeofOpportunity",
         "relations": []
      },
      {
         "typeName": "C_CustomerIndustry",
         "relations": []
      },
      {
         "typeName": "C_CustomerGeographicalScope",
         "relations": []
      },
      {
         "typeName": "C_CustomerOfficeIfMulti",
         "relations": []
      },
      {
         "typeName": "C_TimesheetCategory",
         "relations": []
      },
      {
         "typeName": "C_TopicTopicType",
         "relations": []
      },
      {
         "typeName": "C_UserContractwithwhichlegalentity",
         "relations": []
      },
      {
         "typeName": "C_UserCategory",
         "relations": []
      },
      {
         "typeName": "C_UserBusinessModel",
         "relations": []
      },
      {
         "typeName": "C_UserCurrentHFMEntity",
         "relations": []
      },
      {
         "typeName": "C_UserCurrentLocalFinancialSystemCoCode",
         "relations": []
      },
      {
         "typeName": "C_UserContractStatus",
         "relations": []
      },
      {
         "typeName": "C_CustomerHFMNamedClientPL",
         "relations": []
      },
      {
         "typeName": "C_CustomerCorporateGroupPL",
         "relations": []
      },
      {
         "typeName": "C_CustomerClientSpecificRateCardorCostPlus",
         "relations": []
      },
      {
         "typeName": "C_TimesheetTimesheetCategories",
         "relations": []
      },
      {
         "typeName": "C_UserGroupPTalentType",
         "relations": []
      },
      {
         "typeName": "C_ProjectApproval",
         "relations": []
      },
      {
         "typeName": "C_WorkItemProjectPhase",
         "relations": []
      },
      {
         "typeName": "C_ProjectDiscipline",
         "relations": []
      },
      {
         "typeName": "C_OrganizationCopyofMonths",
         "relations": []
      },
      {
         "typeName": "C_ProjectChannels",
         "relations": []
      },
      {
         "typeName": "C_ProjectProductionBudgetAgreedwithHOD",
         "relations": []
      },
      {
         "typeName": "C_ProjectCreatedbyRegion",
         "relations": []
      },
      {
         "typeName": "C_ProjectBriefValidation",
         "relations": []
      },
      {
         "typeName": "C_ProjectIndustry",
         "relations": []
      },
      {
         "typeName": "C_ProjectGeographicalScope",
         "relations": []
      },
      {
         "typeName": "C_ProjectOffices",
         "relations": []
      },
      {
         "typeName": "C_ProjectProjectFeeorAgencyofRecord",
         "relations": []
      },
      {
         "typeName": "C_DataLeaveType",
         "relations": []
      },
      {
         "typeName": "C_DataAbsenceRequestStatus",
         "relations": []
      },
      {
         "typeName": "C_DataRevenueMonth",
         "relations": []
      },
      {
         "typeName": "C_DataRevenueYear",
         "relations": []
      },
      {
         "typeName": "C_DataReportedRevenueType",
         "relations": []
      },
      {
         "typeName": "C_EnhancementRequestRevenueCategory",
         "relations": []
      },
      {
         "typeName": "C_DataTimeOfDay",
         "relations": []
      },
      {
         "typeName": "C_DataStartDateTimeOfDay",
         "relations": []
      },
      {
         "typeName": "C_DataEndDateTimeOfDay",
         "relations": []
      },
      {
         "typeName": "C_WorkItemBudgetStatusWI",
         "relations": []
      },
      {
         "typeName": "C_UserTimeDisplay",
         "relations": []
      },
      {
         "typeName": "C_UserWeatherDisplay",
         "relations": []
      },
      {
         "typeName": "C_WorkItemKeyDate",
         "relations": []
      },
      {
         "typeName": "C_ProjectBillableProjectType",
         "relations": []
      },
      {
         "typeName": "C_EnhancementRequestMainProjectType",
         "relations": []
      },
      {
         "typeName": "C_CustomerCommercialManager_OLD",
         "relations": []
      },
      {
         "typeName": "C_OrganizationTemplatePrintMode",
         "relations": []
      },
      {
         "typeName": "C_OrganizationTemplateOutput",
         "relations": []
      },
      {
         "typeName": "C_UserGender",
         "relations": []
      }
   ]
}

```
