# License Spitter
Create software licenses with filled fields from your command line.
Install with:
    
    npm i license-spitter -g

### Supported Licenses
- MIT License
- Apache License 2.0
- Mozilla Public License
- ISC License
- General Purpose License
- Lesser General Purpose License
- 3-Clause BSD License
- 2-Clause BSD License
- Common Development And Distrubtion License
- Eclipse Public License 

If you wish for more licenses supported, open a pull request or issue on [GitHub](https://github.com/gadhagod/License-Spitter).

### Commands
    license (View help message)
    license-mit (Creates MIT license)
    license-apache (Creates Apache License 2.0)
    license-mpl (Creates Mozilla Public License)
    license-isc (Creates ISC License)
    license-gpl (Creates General Purpose License)
    license-lgpl (Creates Lesser General Purpose License)
    license-bsd3 (Creates 3-Clause BSD License)
    license-bsd2 (Creates 2-Clause BSD License)
    license-cddl (Creates Common Development and Distribution License)

### Auto-Fill
Licenses' fields are automatically filled. To set the copyright holder's name, run the following command:
    
    export COPYRIGHT_HOLDER='your name'
Replace 'your name' with the copyright holder's name. Without the command above, the copyright holder's name defaults to your machine's username. Copyright year automatically sets to the current year.