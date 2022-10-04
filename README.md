# coder-for-ru
Open-sourse Coder in case of not access of Terraform files in Russia. Added ASP.NET Web App, which download 1.3.0 zip and .json Terraform files (not available in Russia) from link via Web App (fake-http).
There are some problems with ssl - docker container with dotnet doesn't allow to download files with https:// (443 port), download only with http:// (80 port)
