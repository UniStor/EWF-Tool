If you use Guymager to create an EWF Image? This can make it bootable in a VM!

```
image=my-backup.E01
qcow=my-backup.qcow2

ewfexport -l log.txt -t $qcow $image
```
