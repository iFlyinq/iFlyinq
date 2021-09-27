<a href="https://twitter.com/iFlyinqMC/" target="blank"><img src="https://img.shields.io/twitter/follow/iFlyinqMC?logo=twitter&style=for-the-badge" alt="iFlyinqMC"/></a> 
<img src="https://visitor-badge.glitch.me/badge?page_id=iflyinq" alt="iFlyinq visit count"/>

```java
public class iFlyinq extends GitHubUser {

  public iFlyinq() {
    super("iFlyinq", "Belgium");

    this.addLanguage("Java", "C#", "Javascript", "SQL", "PHP");
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
      <img src="https://github-readme-stats.vercel.app/api?username=iFlyinq&count_private=true&show_icons=true&theme=dark&hide_border=false" alt="github stats">
    </td>
    <td>
      <img src="https://github-readme-stats.vercel.app/api/wakatime?username=@iFlyinq&theme=dark&show_iconsk&count_private=true" alt="wakatime stats" height=195>
    </td>
  </tr>
</table>
