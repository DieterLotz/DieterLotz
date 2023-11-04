# Profile

<div align="center">
  <img src="./assets/signals.gif" align="centre" width="50%" height="50%"/>
</div>

### About me :memo:

```js
  const profile = {
    name : 'Dieter',
    surname : 'Lötz',
    age : 25 💫,
    location : 'Cape Town, South Africa 📌',
    likes : [
      'music 🎧',
      'gaming 🎮', 
      'gyming 💪',
      'outdoors 🌳🌊',
      'programming ☕',
      'space exploration 🌍📡'
    ],
    dislikes : [
      '🐑🐑🐑 code'
    ]    
  };
```

### Background :man_technologist: :mag:

#### Tech Stacks

> - Frontend Framworks: Angular, Angular.js & React.js :rocket:
> - Frontend Languages: HTML5, CSS/SCSS, JavaScript, TypeScript 📜
> - Backend: C# / .NET :globe_with_meridians:
> - Databases: Microsoft SQL Server, Postgres SQL :elephant:
> - Development Platform: Windows :computer:
> - Other: Docker :whale:, CI/CD pipelines 🧪, Microservices ➗

#### Education :open_book:

```cs

public static void Main(string[] args)
{
  var tertiaryEducation = new TertiaryEducation
  {
      Qualifications = new List<Qualification>()
      [
        new Qualification(
          Title: "National Diploma: Electrical Engineering",
          Institution: "Cape Peninsula University of Technology",
          Completed: true)
        {
          YearOfCompletion = 2020
        }
      ];
   };

  Console.ReadLine();
}
  
public class TertiaryEducation
{
  public IList<Qualification> Qualifications { get; set; }
}

public sealed record Qualification(string Title, string Institution, bool Completed)
{
  public int? YearOfCompletion { get; set; }
}
```
