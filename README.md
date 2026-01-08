```java
@Data
@AllArgsConstructor
public class Profile {

  private String name;
  private List<String> hobbies;
  private String reachOut;

  public static void main(String[] args) {
    var hobbies = List.of("coding", "photography", "blogging");
    var thoDev = new Profile("Luu Cao Hoang", hobbies, "lcaohoanq.works");
    System.out.println(thoDev);
  }

}
```

<img src="https://komarev.com/ghpvc/?username=lcaohoanq&color=blue&style=flat-square&label=visitors" align="right" />
