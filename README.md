# Pierre's Sweet and Savory Treats

## By **Evgeniya Meshuris**

### This is an application that will allow a user to create an account, add treats and flavors.

## Technologies Used 🖥️

* _C#_
* _.Net 6.0_
* _HTML_
* _CSS_
* _Git_
* _VsCode_
* _EntityFrameWork_
* _REPL_
* _MySQL WorkBench_

## Description ✅

This is an application that will allow a user to create an account, add treats and flavors. User can create an account using email and password. Log in into account. Create Treats and Flavors. Add treats to flavors and add flavors to treats.

## Setup/Installation Requirements 🖊️

* _Clone this repo: <https://github.com/evmeshuris/PierresTreats.Solution.git>_
* _Enter the new directory using the command ```cd PierresTreats.Solution```
* _In the root directory, confirm there is a .gitignore file_
* _add:

```js
*/obj,
*/bin
*.vscode
*/appsettings.json
```

 to the .gitignore file. It will keep your repository clean of unnecessary files and protect your database from unauthorized access_

* _Create an appsetting.json file at the root directory_*
* Open the appsetting.json file and enter:

```js
{ 
  "ConnectionStrings": { 
    "DefaultConnection": "Server=localhost;Port=3306;database=[Database-Name];uid=root;pwd=[Your-Password];" 
  } 
}
```

* _Run ```git add .gitignore```_
* _Commit your changes_
* _To ensure the project will run correctly,_
* _Download MySQL WorkBench_
* _Run ```dotnet tool install --global dotnet-ef --version 6.0.1``` at a global level_
* _Run the Following the project directory of ```PierresTreats```_
* _Run ```dotnet add package Microsoft.EntityFrameworkCore -v 6.0.5```_
* _Run ```dotnet add package Pomelo.EntityFrameworkCore.MySql -v 6.0.1```_
* _Run ```dotnet add package Microsoft.EntityFrameworkCore.Proxies -v 5.0.0```_
* _Run ```dotnet add package Microsoft.AspNetCore.Identity.EntityFrameworkCore -v 6.0.5```_
* _Once all of the necessary setup is in place and we can successfully run dotnet build_
* _Run ```dotnet restore``` and ```dotnet build``` from the PierresTreats directory_
* _Run ```dotnet ef migrations add Initial``` from the PierresTreats Directory_
* _Once we have verified that the migration looks correct and made any necessary changes, we'll run the following command: ```dotnet ef database update```_
* _To interact with the local host website navigate to the University directory and run ```dotnet run```_
* _Click on  <http://localhost:5000>_

## Known Bugs 🐛

* _Currently remove treat is not working_

## License

[MIT](LICENSE)



Copyright (c) 2022, Evgeniya Meshuris
