### Create the MPR: '!MC Users Active'
###
New-FimImportObject -ObjectType ManagementPolicyRule -State Create -Changes @{
    GrantRight                    = 'False'
    Disabled               = 'False'
    DisplayName                   = '!!MC Users Active' 
    Description                   = 'Active Users'
    ManagementPolicyRuleType     = 'SetTransition'    
    ActionType                    = 'TransitionIn'
    ResourceFinalSet              = ('Set', 'DisplayName', '!MC Users Active')
    ActionWorkflowDefinition     = ('WorkflowDefinition','DisplayName','!MC Users Active')  
} -ApplyNow 
