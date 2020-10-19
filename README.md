# 🦀🔠 void-BUild-Data-Injector (BUDI)

Inject information to a RUST build (LIB/EXE).

Add this dependency to your _cargo.toml_:

```
[build-dependencies]
void-budi = {git = "https://github.com/slackmagic/void-budi", branch = "master"}
```

Add this code to your _build.rs_ file (if not present create it on your project root folder):


```
use void_budi::*;
fn main() {
    println!("Hello, world!");
}

```


