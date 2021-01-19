# CheckPoint_VPN_fix_wsl_routes
Powershell script to fix internet connection issue with WSL2 and CheckPoint VPN. It rewrites the route table in your Windows host machine.

#How To
Just run the script in the Windows Powershell as an Administrator:
`.\vpn_fix_wsl_routes.ps1`
You need to run it each time when you was connected by the CheckPoint VPN.
If it dosn't work, make sure you run it as Administrator. By default, we suppose that the *Name* of your WSL2 Network Interface is *vEthernet (WSL)* and *InterfaceDescription* of your CheckPoint Interface has *"Check Point"* words.
