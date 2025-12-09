```csharp
public class MohammedTerfa { 
    // Constructor
    public MohammedTerfa() {
        Name = "Mohammed Terfa";
        Email = "mohammedterfa@gmail.com";
        BackendSkills = new List<string> { 
            "Laravel / PHP", 
            ".NET / C#", 
            "API Development" 
        };
        FrontendSkills = new List<string> { 
            "Vue.js", 
            "Inertia.js", 
            "Livewire", 
            "Nuxt.js", 
            "JavaScript" 
        };
        OtherSkills = new List<string> { 
            "Database Design", 
            "Git & GitHub" 
        };
    }
    
    public string GetSummary() {
        return $"{Name}: Software Developer specializing in Laravel, .NET, and modern web technologies.";
    }
}
```
