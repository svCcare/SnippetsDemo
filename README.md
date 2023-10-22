# Agenda
1. Item Snippets
2. Multi-items Snippets
3. Code Snippets

# Item Snippets

- [ ] Przygotowanie pliku Class.cs
- [ ] Project -> Export Template
- [ ] Konfiguracja templatki
- [ ] Manualny Import: %USERPROFILE%\Documents\Visual Studio <version>\Templates\ItemTemplates
- [ ] Konfiguracja templatki szczegółowa
- [ ] Omówienie plików vstemplate file oraz .cs
- [ ] Dostępne zmienne - Dokumentacja microsoftu -
- [ ] Live coding: Podmiana parametrów
- [ ] Rezultat końcowy

# Multi-file item template
- [ ] Dodanie IMyClass.cs do .zip'a
```
namespace $rootnamespace$
{
// created on $year$ $time$
   public interface $safeitemname$
    {
        public void Method();
    }
}
```

- [ ] Edycja vstemplate
```
<ProjectItem SubType="" TargetFileName="I$fileinputname$.cs" ReplaceParameters="true">IMyClass.cs</ProjectItem>
```
- [ ] Rezultat końcowy

# Code Snippets
- [ ] Utworzenie pliku .xml
- [ ] Uzupełnienie pliku xml, opisanie zawartości
- [ ] Dokumentacja Microsoftu
- [ ] Parametryzacja
- [ ] Import
- [ ] Rezultat końcowy

