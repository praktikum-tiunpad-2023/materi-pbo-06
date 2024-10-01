# Switch dan Enum Class


<div class="grid grid-cols-1 gap-4">

<div v-click="1" class="">

Penggunaan Enum pada Switch

```java
public class Main {
    public static void main(String[] args) {
        Hari pbo = Hari.KAMIS;
        
        switch (pbo) {
            case RABU:
                System.out.println("Prak. Kelas B");
                break;
            case KAMIS:
                System.out.println("Prak. Kelas A");
                break;
            case default:
                System.out.println("Gaada Praktikum");
        }
    }
}
```

</div>
</div>
