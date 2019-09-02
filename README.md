### Dex
---
https://github.com/PatMartin/Dex

```java
// src/com/dexvis/dex/wf/DexJob.java

public interface DexJob
{
  public DexJobState execute() throws DexException;
  
  public void terminate() throws DexException;
  
  public DexJobState start() throws DexException;
  public boolean isTerminated();
  
  public void setState(State stage) throws DexException;
  public Stage getState() throws DexException;
  
  public List<DexTask> getTaskList();
}
```

```
```

```
```


