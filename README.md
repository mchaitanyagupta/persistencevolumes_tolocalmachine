 created persistance volume with local storage
 -files
   persistence valoume(pv)
   persistance volume claim(pvc)
   storage class(local-storage)
   deployment
key code:
used volume mounts
  name,mountpath
volumes sections
  name
    persistence volume
      claimname
        pvc
storage class provider: kubernetes.io/noprovider  //tells that no cloud provider
pvc:
  accessmode: readwritemany
  reclaim policy:
    retain/delete
kind:deployment,persistencevolumeclaim,persistence volume,storage-class

  
