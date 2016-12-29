#Apollo demo instructions

With your Red Hat email address, join the Ansible Tower Demo Slack Team https://ansibletowerdemo.slack.com and go to #tower_notify channel to see notifications from your demo job runs.

1. Run Job Template __D1 - Launch RHEL Instances__
   * Select __Username Inventory__ when prompted.
2. Run Job Template __D2 - Check ICMP Configuration__
3. Test ICMP
   * Select __INVENTORIES / Username INVENTORY / AP-SOUTHEAST-1B / TAGS / TAG_ANSIBLE_GROUP__
   * Copy the __IP Address__ appearing on the right side (under HOSTS)
   * Paste the __IP Address__ on a new command line window
   * Ping x.x.x.x
   * Select __Username Inventory__ when prompted.
4. Run Job Template __D3 - Disable ICMP__
   * Select __Username Inventory__ when prompted.
5. Test ICMP again using Step 3. You will find it disabled.
6. Run Job Template __D4 - Enable ICMP__
7. Test ICMP again using Step 3. You will find it enabled. 
6. Run Job Template __D5 - Clean up instances__
