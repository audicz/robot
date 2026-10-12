Opravené soubory pro Robot Cockpit

Oprava:
- Java sourceCompatibility a targetCompatibility jsou nastavené na 17.
- Kotlin jvmToolchain i compilerOptions jvmTarget jsou nastavené na 17.
- Workflow pro GitHub Actions je přiložený.

Použití:
1. Rozbal ZIP v počítači.
2. Zkopíruj soubory do stejnojmenných cest v kořeni repozitáře Robot007 a přepiš původní soubory.
3. Proveď commit a push.
4. V GitHub Actions otevři nový běh Build Robot Cockpit APK.

Hlavní oprava je v app/build.gradle.kts.
