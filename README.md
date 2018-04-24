# ocp39_pre
- Change vars in the docker-storage role file "docker-storage-setup" to match the correct DEVS=<disk> VG=<VG-NAME>
  
- Openshift Docker storage assumes during the pre-reqs that you want to use and overlay protocol for docker storage. Make sure you have your docker-storage-setup in place before running the pre-reqs that come with openshift installer for V3.9
