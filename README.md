
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
  </tr>
</table>
