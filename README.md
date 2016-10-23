# Chat
A simple client-server chat implementation based on WCF.

Server part - WCF service, hosted in a console application (or IIS). Currently no security used. Listens to a 808 port in duplex mode using net.tcp protocol.  
Client part - a WinForms and a WPF application. Currently in the process of migrating on Universal Windows Platform.

Requires .NET Framework 4.6.1. 

Used libraries:  
[NUnit](https://github.com/nunit/nunit)  
[Moq](https://github.com/moq/moq)  
[NLog](https://github.com/NLog/NLog)  
[MahApps.Metro](https://github.com/MahApps/MahApps.Metro/)  
[MvvmLight](https://mvvmlight.codeplex.com/)  
[Autofac](https://github.com/autofac/Autofac)  