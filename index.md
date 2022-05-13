## Welcome to GitHub Pages

# Jenkins

Jenkins to open-source’owe narzędzie pozwalające zautomatyzować wytwarzanie oprogramowania. Jego główną funkcjonalnością jest tworzenie pipeline’ów dla ciągłej integracji, ciągłego dostarczania i ciągłego wdrażania. Projekty w Jenkinsie można tworzyć na kilka sposobów.

## Projekt ogólny
![Image](https://github.com/mbielak1/mbielak1.github.io/blob/9bfe9e540b4245e57496c243707763ea9580b151/Obraz1.png)
<br />
Łatwe w użycie. Dobra opcja do zrobienia automatyzacji na szybko. Rozbudowany interfejs graficzny pozwala się przeklikać przez wszystkie opcje.

## Pipeline
![Image](https://github.com/mbielak1/mbielak1.github.io/blob/6a1347e1185ae11a32dd6e6fe65f087cf3398ef8/Obraz2.png)
<br />
https://github.com/mbielak1/mbielak1.github.io/blob/6a1347e1185ae11a32dd6e6fe65f087cf3398ef8/Obraz2.png
Pozwala na tworzenie rozbudowanych pipelinów przy użyciu własnoręcznie napisanych skryptów. Mamy większe opcje customizacji niż w przypadku projektu ogólnego. Ten rodzaj służy do robienia pipelinów na jednym branchu. Przy tworzeniu własnych skryptów bardzo pomocny jest generator Jenkinsa „Pipeline Syntax”. Można się do niego dostać z poziomu ekranu głównego pipeline’u albo w oknie konfiguracji. Generator wyświetla okno do wpisywania jak w projekcie ogólnym i pozwala wygenerować odpowiadający wybranym opcjom skrypt jenkinsowy.
![Image](https://github.com/mbielak1/mbielak1.github.io/blob/6a1347e1185ae11a32dd6e6fe65f087cf3398ef8/Obraz4.png)
<br />
## Multibranch pipeline
![Image](https://github.com/mbielak1/mbielak1.github.io/blob/6a1347e1185ae11a32dd6e6fe65f087cf3398ef8/Obraz3.png)
<br />
Opcja dla dużych projektów. Umożliwia te same opcje co zwykły pipeline, ale dla wielu branchy.

## Pluginy

Dużą zaleta Jenkinsa jest możliwość dostosowania do naszych potrzeb. Można zainstalować pluginy do wielu znanych narzędzi np. SonarQube, Nexus repository. Po zainstalowaniu pluginu dodatkowe opcje pojawiają się za równo dla projektu ogólnego w postaci okienka do przeklikania jak i dla pipeline’ów jako komenda do wywołania.


