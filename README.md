# Servicenow
New Repository
var callerId = g_form.getReference('caller_id', populateEmail);

function populateEmail(caller){
g_form.setValue('description', caller.email);
}
