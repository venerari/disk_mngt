# Disk Management

Note: This is only for raw disk, meaning empty raw disk no partition yet.  <\n> 
      The /dev/sd[x] don't have yet /dev/sd[x]1 or nothing will be created.  <\n>
      This also can partition mpath[x].  \n
      In the future, I will add second partitioning and so on.  \n
      The size of disk to search can be changed which is defaulted to 10GB. \n
      
Instructions: 
      Edit first the dynatrace_tps.ini and put the server(with fqdn). \n
      Run the get_raw_disk tag, it will create another inventory called partition.ini  \n
      You may run pre_check tag first to do pre-checking.  \n
      Then you can run the create_partition tag.  \n
