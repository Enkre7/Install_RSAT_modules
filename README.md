Les modules RSAT sont nécessaires pour utiliser les commandes d'administrateur systèmes & réseaux. Notamment il sert à obtenir les commandes de gestion d'Active Directory.

#### Pour lister les packages facultatifs et indiquer ceux installés:

```powershell
	DISM.exe /Online /Get-Capabilities
```


#### Pour Installer tout les packages RSAT:

```powershell
	Add-WindowsCapability –online –Name  “Rsat.ServerManager.Tools~~~~0.0.1.0”
	Add-WindowsCapability –online –Name  “Rsat.ActiveDirectory.DS-LDS.Tools~~~~0.0.1.0”
	Add-WindowsCapability –online –Name  “Rsat.BitLocker.Recovery.Tools~~~~0.0.1.0”
	Add-WindowsCapability –online –Name  “Rsat.CertificateServices.Tools~~~~0.0.1.0”
	Add-WindowsCapability –online –Name  “Rsat.DHCP.Tools~~~~0.0.1.0”
	Add-WindowsCapability –online –Name  “Rsat.Dns.Tools~~~~0.0.1.0”
	Add-WindowsCapability –online –Name  “Rsat.FailoverCluster.Management.Tools~~~~0.0.1.0”
	Add-WindowsCapability –online –Name  “Rsat.FileServices.Tools~~~~0.0.1.0”
	Add-WindowsCapability –online –Name  “Rsat.GroupPolicy.Management.Tools~~~~0.0.1.0”
	Add-WindowsCapability –online –Name  “Rsat.IPAM.Client.Tools~~~~0.0.1.0”
	Add-WindowsCapability –online –Name  “Rsat.LLDP.Tools~~~~0.0.1.0”
	Add-WindowsCapability –online –Name  “Rsat.NetworkController.Tools~~~~0.0.1.0”
	Add-WindowsCapability –online –Name  “Rsat.NetworkLoadBalancing.Tools~~~~0.0.1.0”
	Add-WindowsCapability –online –Name  “Rsat.RemoteAccess.Management.Tools~~~~0.0.1.0”
	Add-WindowsCapability –online –Name  “Rsat.RemoteDesktop.Services.Tools~~~~0.0.1.0”
	Add-WindowsCapability –online –Name  “Rsat.ServerManager.Tools~~~~0.0.1.0”
	Add-WindowsCapability –online –Name  “Rsat.Shielded.VM.Tools~~~~0.0.1.0”
	Add-WindowsCapability –online –Name  “Rsat.StorageMigrationService.Management.Tools~~~~0.0.1.0”
	Add-WindowsCapability –online –Name  “Rsat.StorageReplica.Tools~~~~0.0.1.0”
	Add-WindowsCapability –online –Name  “Rsat.SystemInsights.Management.Tools~~~~0.0.1.0”
	Add-WindowsCapability –online –Name  “Rsat.VolumeActivation.Tools~~~~0.0.1.0”
	Add-WindowsCapability –online –Name  “Rsat.WSUS.Tools~~~~0.0.1.0”
```
