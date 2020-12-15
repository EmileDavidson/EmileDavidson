
```java
public class Tundersz extends GitHubUser {

  public Tundersz() {
    super("Tundersz", "Netherlands");

    this.addLanguage("Java", "C#", "Javascript", "c++", "html", "css");
  }
}

public abstract class GitHubUser {

  private final String name;
  private final String country;

  private ArrayList<String> languages = new ArrayList<>();

  public GitHubUser(String name, String country) {
      this.name = name;
      this.country = country;
  }

  public void addLanguage(String... language) {
    languages.addAll(language);
  }
}
```

<table>
  <tr>
    <td>
      <img src="https://github-readme-stats.vercel.app/api?username=EmileDavidson&count_private=true&show_icons=true&theme=dark&hide_border=false" alt="github stats">
    </td>
    <td>
      <img src="https://wakatime.com/share/@473cdb6f-e715-4a87-a826-00b4d12ab7b6/ffd64ccb-d89a-44b1-96a5-837c4f3a9cda.svg" alt="wakatime stats" height=195>
    </td>
  </tr>
</table>
