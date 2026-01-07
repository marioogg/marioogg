### Hey 👋

I'm Mario, I code useless things

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
                getLogger().log(Level.INFO, "https://e-z.bio/marioogg")
                break;
            case DISCORD:
                getLogger().log(Level.INFO, "marioogg")
                break;
            case EMAIL:
                getLogger().log(Level.INFO, "mario@reals.lat")
                break;
    }
}
```
