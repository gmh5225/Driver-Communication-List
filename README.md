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
