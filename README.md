```C#

internal class Jbeast291{

  [Register("Main")]
  private static void RegisterLanguages()
  {
     PersonRegsitry.main.Register("Jbeast291")
        .WithPronouns("He/They");
  }

  [Register("Languages", "Main")]
  private static void RegisterLanguages()
  {
     LanguageHandler.main.Register("C#", "Java", "GDScript");
  }
  
  [Register("Projects", "Main")]
  private static void RegisterProjects()
  {
     ProjectHandler.main.RegsiterAsTeamMember("Beneath The Waves") // https://github.com/BeneathTheWaves
        .WithDescription("Lead Systems Engineer")
        .WithDescription("Lead Developer On Abyss Editor");
  
     ProjectHandler.main.RegsiterAsTeamMember("The Red Plague") // https://github.com/ThePlagueSpreads
        .WithDescription("Ice Dragon Mod")
        .WithDescription("I know a person who knows another person who knows another person who programs trp");
  
    ProjectHandler.main.regsiterPersonal("PersonalMods"); // https://github.com/jbeast291/Subnautica-mod
  }
}
```
