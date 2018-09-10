# Servicio de envio de Emails

El objetivo es crear un servicio de envio de emails que soporte archivos comprimidos y adjuntos.

## Informaci�n

### Envio de emails con la librer�a de .NET

**System.Net.Mail: ** es la libreria de .NET para el envio de emails.

Reemplazar los parametros del servicio: ***NetEmailService***

Soporta archivos comprimidos, archivos adjuntos y exchange.

![Screenshot](Screenshots/netemail.png)

***Doc oficial: *** https://msdn.microsoft.com/es-es/library/system.net.mail(v=vs.110).aspx

### Envio de emails con la librer�a de SendGrid

***SendGrid.Helpers.Mail: *** es la libreria de SendGrid para el envio de emails.

Reemplazar los parametros del servicio: ***SendGridEmailService***

Soporta archivos comprimidos y adjuntos.

***Doc oficial: *** https://github.com/sendgrid/sendgrid-csharp

### Resultado

![Screenshot](Screenshots/console.png)

## Testeado

- Visual Studio 2017

- .Net Core 2.x

- C# 7.x