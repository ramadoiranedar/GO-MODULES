git init
git remote add origin https://github.com/ramadoiranedar/GO-MODULES.git
go mod init https://github.com/ramadoiranedar/GO-MODULES.git
git add .
git commit -m "create go_modules"
git push origin main
git tag v1.0.0
git push origin v1.0.0

<!-- download that package to other module -->
go get github.com/ramadoiranedar/go-modules

