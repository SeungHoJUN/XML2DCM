---
# XML2DCM

XML2DCM은 XML 형태의 데이터를 Dicom 형태로 바꾸는 패키지 입니다. ( 여기서 XML 데이터는 ECG 데이터를 담고 있습니다. )

XML2DCM is a package that converts XML formatted data into Dicom format. ( the XML data contains ECG information. )

---

# XML Structure

XML 파일을 DCM 으로 변환하기 때문에 XML 파일의 형태가 중요합니다.
다음과 같은 [구조](https://github.com/SeungHoJUN/XML2DCM/blob/main/xml_format.txt)를 가지고 있습니다. 파일 변환 전 해당 형태를 띄고 있는지 확인이 필요합니다.

The format of the XML file is crucial for its conversion to a DCM file. It must conform to the following [structure](https://github.com/SeungHoJUN/XML2DCM/blob/main/xml_format.txt). Please verify that the file matches this structure before converting.

---

# To start using xml2dcm

## Install

### PIP
```
pip install xml2dcm
```

```
python -m pip install --upgrade xml2dcm
```


## Using the XML2DCM Library in Python
```
from xml2dcm import xml2dcm
xml2dcm.create_dicom_file('xml_file_path\XML_file.xml')
```

---

# license

This software is licensed under the Apache 2 license, quoted below

Copyright 2024 seunghojun

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
