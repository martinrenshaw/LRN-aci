#A playbook to loop through vars in a file

This playbook 'aci-playbook.yaml' does the following.

- creates multiple tennant
- under the tenant create all the vrfs listed in the var file
- under the tenant create a BD linked to the vrfs
- under the tenant create a BD subnet 