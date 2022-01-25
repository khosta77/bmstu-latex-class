# LaTeX-класс `bmstu`

<a href='https://www.ctan.org/pkg/bmstu'>![Version shield](https://img.shields.io/ctan/v/bmstu)</a>
<a href='https://www.latex-project.org/lppl/'>![License shield](https://img.shields.io/ctan/l/bmstu)</a>
![TestVKR build shield](https://img.shields.io/badge/TestVKR%20build-203-blue)

LaTeX-класс `bmstu` призван упростить создание отчетов и расчетно-пояснительных записок студентами МГТУ им. Н. Э. Баумана. Пакет, содержащий класс, размещен в CTAN и [**доступен для загрузки**](https://ctan.org/pkg/bmstu).

К особенностям класса можно отнести:
* генерацию титульных листов для всех основных типов работ — лабораторных, курсовых, научно-исследовательских, дипломных;
* генерацию реферата с подсчетом количества объектов;
* генерацию списков определений и сокращений;
* генерацию других шаблонных элементов документа;
* команды для упрощения работы с изображениями, листингами и пр.

Сгенерированные файлы соответствуют [**требованиям МГТУ им. Н. Э. Баумана**](https://mf.bmstu.ru/info/uu/ot/norm_docs/docs/polozhenie_normcontrol_pril1.pdf) и [**ГОСТ 7.32-2017**](https://docs.cntd.ru/document/1200157208). Расчетно-пояснительные записки к выпускным квалификационным работам успешно проходят проверку программы TestVKR (сборка 203).

Примеры использования команд и окружений представлены в файлах [examples.tex](bmstu/examples/examples.tex) и [examples.pdf](bmstu/examples/examples.pdf). Приведены шаблоны для разработки [отчетов](templates/report/), [расчетно-пояснительных записок к курсовым работам](templates/coursework/), [отчетов по научно-исследовательским работам](templates/research/) и [расчетно-пояснительных записок к выпускным квалификационным работам](templates/thesis/).

## Установка

Перед установкой класса убедитесь, что установлен один из дистрибутивов LaTeX.

### Установка из CTAN

Так как класс размещен в CTAN, можно выполнить автоматическую установку пакета.

#### Linux (TeX Live)
```bash
sudo tlmgr install bmstu
```

### Ручная установка

Если по какой-то причине автоматическая установка невозможна, необходимо установить класс вручную. Для этого следует добавить пакет в texmf-дерево пользователя.

#### Linux (TeX Live)

```bash
git clone https://github.com/Orianti/bmstu-latex-class.git
cd bmstu-latex-class/
mkdir -p $(kpsewhich -var-value TEXMFHOME)/tex/latex/ && cp -R bmstu $_
```

## Лицензия

Файлы, перечисленные в `manifest.txt`, распространяются по лицензии [**The LaTeX Project Public License**](https://www.latex-project.org/lppl/).

Файл `bmstu-logo.pdf` является гербом МГТУ им. Н. Э. Баумана и защищен авторским правом. Распространяется по принципам свободного использования произведений (ст. 1274 ГК РФ).

---

Copyright © Новиков М. Р., 2020–2022<br>
