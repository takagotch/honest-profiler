### honest-profiler
---
https://github.com/jvm-profiling-tools/honest-profiler

```java
// src/main/java/com/insightfullogic/honest_profiler/core/platform/Platforms.java

public class Platforms
{
  private Platforms() {}
  
  public static String getDynamicLibraryExtension()
  {
    if (isOsx())
    {
      return ".dylib";
    }
    
    return ".so";
  }
  
  private static boolean isOsx()
  {
    return getOsName().toUpperCase().contains("MAC");
  }
  
  private static String getOsName()
  {
    return System.getProperty("os.name");
  }
}
```

```
```

```
```


