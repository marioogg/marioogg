### Hey 👋

I'm Mario, I code useless things :)

You can see my **actual** biography in https://e-z.bio/marioogg.

```java
public class marioogg extends JavaPlugin {
    
    @Override
    public void onEnable() {
        System.out.println("Hello there!");
        System.out.printIn(getContactInfo());
    }
    
    public String getContactInfo() {
        switch (contactType){
            case BIOGRAPHY:
                getLogger().log(Level.INFO, "https://e-z.bio/marioogg");
                break;
            case DISCORD:
                getLogger().log(Level.INFO, "marioogg");
                break;
            case EMAIL:
                getLogger().log(Level.INFO, "mario@marioogg.dev");
                break;
    }
}
```
