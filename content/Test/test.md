---
title: 'Markdown Test'
description: 'Markdown Testing File'
catergory: 'Research'
tags: ['Test', 'Home']
titleIcon: "fa-sharp fa-solid fa-flask"
---

# Markdown Testing File

## Text Differentiating

Regular text

~~Striked Text~~

**Bolded Text**

| Table | Table |
|:---:|:----:|
|Content | |
| | Content |

# Code

## Inline Code

`sudo apt-get install`

## Block Style

C++

```cpp
#include <iostream>

using std::cout;

int main() {
    cout << "Hello World!";
    return 0
}
```

JavaScript

```js
app.get('/legacyparts', async (req, res) => {
  connection.connect((error) => {
    if (error) {
      console.error(ERROR + 'connecting to database:', error);
    } else {
      console.log(SUCCESS + "Connected to Legacy Database");
    }
  });
  console.log(API + "Legacy Parts Endpoint")
  const perPage = parseInt(req.query.per) || 10;
  let page = parseInt(req.query.page) || 1;
  const offset = (page - 1) * perPage;

  connection.query(`SELECT * FROM parts LIMIT ${perPage} OFFSET ${offset}`, (error, results) => {
    if (error) {
      console.error(ERROR + "In /legacyparts: " + error);
      res.status(500).send('Error retrieving data from database');
    } else {
      console.log(API + "Fetch " + perPage + " items with offset " + offset);
      res.send(results);
    }
  });
});
```

PowerShell

```ps1
## Define the service name in a variable
$ServiceName = 'EventLog'

## Read the service from Windows to return a service object
$ServiceInfo = Get-Service -Name $ServiceName

## If the server is not running (ne)
if ($ServiceInfo.Status -ne 'Running') {
	## Write to the console that the service is not running
	Write-Host 'Service is not started, starting service'
	## Start the service
	Start-Service -Name $ServiceName
	## Update the $ServiceInfo object to reflect the new state
	$ServiceInfo.Refresh()
	## Write to the console the Status property which indicates the state of the service
	Write-Host $ServiceInfo.Status
} else { ## If the Status is anything but Running
	## Write to the console the service is already running
	Write-Host 'The service is already running.'
}
```
