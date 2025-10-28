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
