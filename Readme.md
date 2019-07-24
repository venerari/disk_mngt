# Disk Management

Note: This is only for raw disk, meaning empty raw disk no partition yet.  <br> 
      The /dev/sd[x] don't have yet /dev/sd[x]1 or nothing will be created.  <br>
      This also can partition mpath[x].  <br>
      In the future, I will add second partitioning and so on.  <br>
      The size of disk to search can be changed which is defaulted to 10GB. <br>
      
Instructions: 
      Edit first the dynatrace_tps.ini and put the server(with fqdn). <br>
      Run the get_raw_disk tag, this will create email.txt (or go to your email)  <br>
      Copy the content and paste it on partition.ini  <br>
      You may run pre_check tag first to do pre-checking.  <br>
      Then you can run the create_partition tag with partition.ini inventory.  <br>

## Note: This is not tested on Redhat 5.  Only redhat 6/7.
