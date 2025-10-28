<!-- 👩‍💻 JAHNVI RAWAT - .NET DEVELOPER -->

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:8A2BE2,100:00BFFF&height=200&section=header&text=👩‍💻%20Jahnvi%20Rawat%20%7C%20.NET%20Developer&fontSize=35&fontColor=ffffff&animation=fadeIn)

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=25&pause=1000&color=8A2BE2&center=true&vCenter=true&width=600&lines=Hi%2C+I'm+Jahnvi+Rawat!;A+.NET+Developer+From+India;Building+Scalable+and+Clean+Apps+💻)](https://git.io/typing-svg)

---

### 🧩 **About Me**

```csharp
using DeveloperPortfolio;

interface IDeveloperProfile
{
    string Name { get; }
    string Title { get; }
    void Introduce();
}

class StudentDeveloper : IDeveloperProfile
{
    public string Name => "Jahnvi Rawat";
    public string Title => ".NET Developer";

    public void Introduce() =>
        Console.WriteLine($"👋 Hi, I'm {Name}, a {Title} passionate about crafting clean, efficient, and scalable web applications.");
}

public class Bio : StudentDeveloper
{
    public string Company  = "Mphasis | Associate Software Developer";
    public string Location = "Haridwar, Uttarakhand, IN";
    public string Email    = "jahnvirawat20@gmail.com";
    public string LinkedIn = "linkedin.com/in/jahnvi-rawat";
    public string GitHub   = "github.com/JahnviRawat";
}

public class Skills : StudentDeveloper
{
    public string[] Languages  = { "C#", "C++", "JavaScript", "TypeScript" };
    public string[] Frameworks = { ".NET Core", "ASP.NET MVC", "Entity Framework", "Angular", "Bootstrap" };
    public string[] Databases  = { "SQL Server", "DBMS Concepts" };
    public string[] Tools      = { "Git", "GitHub", "Visual Studio", "Linux CLI", "Shell Scripting" };
    public string[] Projects   = {
        "🧬 Vaccine Management System — ASP.NET Core MVC, Web API, Unit Testing",
        "🧾 Customer Management — WinForms, Entity Framework",
        "🍕 Cheese Drip — Angular, TypeScript, Bootstrap"
    };
}

