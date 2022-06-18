# Driver-Communication-List
Driver-Communication-List

## Sample 1 2022.5.18
> User
``` C++
win32u.dll.ZwDxgkGetAvailableTrackedWorkloadIndex
```
> Kernel
``` C++
win32k.sys.NtDxgkGetAvailableTrackedWorkloadIndex ->
  win32base.sys.NtDxgkGetAvailableTrackedWorkloadIndex ->
    dxgkrnl.sys.NtDxgkGetAvailableTrackedWorkloadIndex
```

## Sample 2 2022.5.27
> User
```
win32u.dll.NtUserGetThreadState
```
> Kernel
```
win32k.sys.NtUserGetThreadState
```


## Sample 3 2022.6.17
> User
``` C++
win32u.dll.ZwFlipObjectReadNextMessageToProducer
```
> Kernel
``` C++
win32k.sys.NtFlipObjectReadNextMessageToProducer ->
  win32base.sys.NtFlipObjectReadNextMessageToProducer ->
    dxgkrnl.sys.NtFlipObjectReadNextMessageToProducer
```

