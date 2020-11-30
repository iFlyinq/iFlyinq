<a href="https://twitter.com/iFlyinq/" target="blank"><img src="https://img.shields.io/twitter/follow/iFlyinq?logo=twitter&style=for-the-badge" alt="iFlyinq"/></a> 
<img src="https://visitor-badge.glitch.me/badge?page_id=iflyinq" alt="iFlyinq visit count"/>

```java
public class iFlyinq extends GitHubUser {

  public iFlyinq() {
    super("iFlyinq", "Belgium");

    this.addLanguage("Java", "C#", "Javascript", "SQL");
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
![iFlyinq's github stats](https://github-readme-stats.vercel.app/api?username=iFlyinq&count_private=true&show_icons=true&theme=dark&hide_border=false) 
![iFlyinq's github top langs](https://github-readme-stats.vercel.app/api/top-langs/?username=iFlyinq&theme=dark&count_private=true)

