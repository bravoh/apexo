# Apexo Dental Clinic Manager

A web/desktop application to manage your dental clinic practice.

-   [More Info](https://apexo.app)
-   [Documentation](https://docs.apexo.app)
-   [Demo Application](https://demo.apexo.app)
-   [Web Application](https://web.apexo.app)
-   [Download](https://github.com/alexcorvi/apexo/releases/)

#### Embedded Apps that can be used separately

-   [Orthograph](https://orthograph.apexo.app), [repo](https://github.com/alexcorvi/orthograph)
-   [Cephalometric](https://cephalometric.apexo.app), [repo](https://github.com/alexcorvi/cephalometric)

## Changelog

# 2.2.1

-   Sorting calendar appointments according to time

# 2.2.0

-   Deleting cephalometric analysis is now possible
-   Unifying height now works on opening the calender module
-   New Feature: Setting appointments exact time

# 2.1.2

-   Fixed non latin album names passed to Apexo

### 2.1.1

-   Fixed remote DB credentials

### 2.1.0

-   New feature: compaction on local and remote databases
-   New feature: compaction automation
-   Orthograph is now using the dropbox for storage
-   better UX on choosing duty days
-   better UX on choosing operating doctors

### 2.0.0

-   New feature: backup automation to Dropbox
-   New feature: users can be assistants or other staff members
-   New feature: user level and permission
-   New feature: user login PIN
-   New feature: Embedded Apps: Orthograph, Cephalometric
-   New feature: optional info taking

### 1.7.1

-   You can enter either birth year or age

### 1.7.0

-   Remove appointment date filters
-   limit data table rows
-   backing up and restoring using files
-   fixed issues in backing up and restoring

### 1.6.5

-   Graceful errors

### 1.6.4

-   Fixed: open appointments editor when creating the first appointment
-   Appointment notes instead of diagnosis and complaint
-   Ortho: Appliances & Modifications
-   Save login data more persistently

### 1.6.3

-   open item after creating
-   sort treatments alphabetically

### 1.6.2

-   Critical bug fixes

### 1.6.1

-   Performance improvements
-   improved searching capabilities
-   Fixed bug: calendar day height unification
-   Fixed bug: sorting by numerical columns

### 1.6.0

-   Consistent and responsive experience across all small screens
-   Consistent experience across modules
-   Consistent data manipulation experience
-   Fixed bug: labeled appointments in safari
-   Fixed bug: profit percentage calculation
-   New feature: Expenses per unit
-   New feature: hide/show doctor contact details
-   New feature: prescriptions units per time

### 1.5.5

-   Consistencies with panel headings
-   Solved few responsiveness issues
-   Random dates for appointments on demo
-   Fixed minor bugs

### 1.5.4

-   Fixed few bugs

### 1.5.2

-   Minor improvements concerning responsiveness

### 1.5.1

-   removed ant.design dependency

### 1.5.0

-   scroll to day when selecting it on the appointments page
-   moved inline styles to their respective SCSS file when applicable
-   fixed issue where tomorrow's appointments won't be viewed if it's the last day of the month
-   replaced NVD3 with chart.js for better bundle size and performance
-   loading demo data using restore functionality
-   fixed an issue where authentication occurring multiple times.

### 1.4.2

-   updated pouchdb-browser to latest release (7.0.0) and thus fixed the iOS idb issue

### 1.4.1

-   added missing icons

### 1.4.0

-   multiple demo hosts
-   fixed safari date issues (statistics & calendar modules)
-   added backup / restore feature

## License

The MIT License (MIT)

Copyright (c) 2019 Alex Corvi

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
