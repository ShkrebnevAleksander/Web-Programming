# My Curriculum Vitae
![Avatar](https://i.pinimg.com/736x/a8/7d/e9/a87de9269ce69f813a8eaf0021927443.jpg)
### Personal Info
- Name: Aleksandr Shkrebnev
- Contacts: phone: +375(44)721-35-59, email: shkrebnev.aleksander@example.com
### About Me
I want to become a professional .NET Developer. I am interested in backend development. Currently, I am studying at the university and learning C#.

### Skills
* C#, .NET Core
* HTML, CSS, SQL (PostgreSQL)
* Git, Docker

### Code Example
C# Web API Controller:

```csharp
[HttpGet("{id}")]
public ActionResult<string> GetUserInfo(int id) {
    var user = _userService.GetById(id);
    return Ok(user.Name);
}
```
