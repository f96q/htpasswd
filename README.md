htpasswd Cookbook
=================

Generate htpasswd.

unused htpasswd command.

#### htpasswd::default
<table>
  <tr>
    <th>Key</th>
    <th>Type</th>
    <th>Description</th>
    <th>Default</th>
  </tr>
  <tr>
    <td><tt>['htpasswd']['dir']</tt></td>
    <td>String</td>
    <td>htpasswd dir</td>
    <td><tt>/etc/nginx/htpasswd.d</tt></td>
  </tr>
</table>

Usage
-----
#### htpasswd::default

```json
{
  "deploy": {
    "app_name": {
      "htpasswd" : {
        "username": "user",
        "password": "pass"
      }
    }
  }
}
```

Contributing
------------
1. Fork the repository on Github
2. Create a named feature branch (like `add_component_x`)
3. Write your change
4. Write tests for your change (if applicable)
5. Run the tests, ensuring they all pass
6. Submit a Pull Request using Github

License and Authors
-------------------
* Author: danny (danny.dev8@gmail.com)
* License: MIT

