# Disk Management

Note: This is only for raw disk, meaning empty raw disk no partition yet.  <br> 
      The /dev/sd[x] don't have yet /dev/sd[x]1 or nothing will be created.  <br>
      This also can partition mpath[x].  <br>
      In the future, I will add second partitioning and so on.  <br>
      The size of disk to search can be changed which is defaulted to 10GB. <br>
      
Instructions: 
      Edit first the dynatrace_tps.ini and put the server(with fqdn). <br>
      Run the get_raw_disk tag, it will create another inventory called partition.ini  <br>
      You may run pre_check tag first to do pre-checking.  <br>
      Then you can run the create_partition tag.  <br>
