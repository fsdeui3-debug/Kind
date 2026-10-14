# AntiKB Fabric 26.3 — cloud build

This project is configured for Minecraft 26.3, Fabric Loader 0.19.5, Java 25,
and Mod Menu 21.0.0. The Mod Menu version placeholder has been replaced.

## Build it without installing Java or Gradle on your phone

1. Create a repository on GitHub.
2. Upload the contents of this `antikb` folder to the repository (the `.github` folder must be included).
3. Open the repository's **Actions** tab.
4. Select **Build AntiKB JAR** and tap **Run workflow** (or wait for the first push build).
5. Open the completed workflow run. Under **Artifacts**, download `AntiKB-Fabric-26.3`.
6. Extract the downloaded artifact ZIP. Put the `.jar` inside your Minecraft instance's `mods` folder.

If the build fails, open the workflow run and check the **Build mod** step's error log. This project has not been compiled in this environment, so a successful build is not guaranteed until GitHub Actions finishes.
