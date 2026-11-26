# PubChem 약물 정보 조회 앱

PubChem PUG REST API로 일상 약물 **Acetaminophen(타이레놀)** 의 특성 정보를 조회해 웹 화면에 보여주는 앱입니다.

### ▶ [앱 실행하기](https://wlgud314-code.github.io/pubchem-drug-app/)

## 조회 정보
- PubChem CID, 분자식, 분자량, IUPAC 이름
- XLogP, 수소결합 공여체/수용체 수, SMILES
- 2D 구조 이미지

## 사용 API
```
GET https://pubchem.ncbi.nlm.nih.gov/rest/pug/compound/name/acetaminophen/property/MolecularFormula,MolecularWeight,IUPACName,XLogP,HBondDonorCount,HBondAcceptorCount,CanonicalSMILES/JSON
GET https://pubchem.ncbi.nlm.nih.gov/rest/pug/compound/name/acetaminophen/PNG
```

## 실행 방법
`index.html` 파일을 브라우저로 열고 **정보 조회하기** 버튼을 누르면 됩니다. 설치할 것은 없습니다.
