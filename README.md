# servicenow_network_tickets
Ansible role for ServiceNow network tickets


Makes sure to create the `device uptime` & `ios version` fields in your ServiceNow incident template.
 This is exaplained in the blog post below.

The `hostname` parameter has now also been added in the data section of the API call. Make sure to create that field in your incident template in SNOW.

https://www.thenetwork.engineer/blog/utilize-ansible-for-opening-and-closing-tickets-with-servicenow-part3
