---
layout: post
title:  "판교 단독주택 정리"
date:   2017-02-03 09:54:22 +0900
categories: 자료
tags: 판교 운중동 단독주택 건축가 시공사 땅콩주택 듀플렉스
---

<div id="map" style="width:100%;height:600px;"></div>

<script type="text/javascript" src="https://openapi.map.naver.com/openapi/v3/maps.js?clientId=O9eVjL1IphOxrVTcB0Uk"></script>
<script>

var infos = [
    ["온당", 127.096382, 37.4016035],
    ["소소원", 127.0940359, 37.4025029],
    ["함양재", 127.0977068, 37.400278],
    ["무이동", 127.0992295, 37.396576],
    ["AD Fontes", 127.0973557, 37.399659],
    ["동/서안재", 127.0939312, 37.4020216],
    ["시전당", 127.0979108, 37.4008404],
    ["One Roof House", 127.0983947, 37.3999584],
    ["층층마루집", 127.0957756, 37.4014999],
    ["호연당", 127.093291, 37.4019889],
    ["삼대헌", 127.0953177, 37.4023279],
    ["TIMBER DUPLEX 1", 127.100289, 37.389514],
    ["POP House", 127.0693863, 37.3893289],
    ["이보재", 127.0996546, 37.3954831],
    ["HESED", 127.1009825, 37.3873983],
    ["동행", 127.0993804, 37.3933808],
    ["사이집", 127.0989368, 37.3933657],
    ["도시채", 127.0695033, 37.38974],
    ["흰벽돌집", 127.0990391, 37.3869491],
    ["계수나무집", 127.0659444, 37.3926041],
    ["IZIP", 127.0982138, 37.397695],
    ["YELLOW WOOD HOUSE", 127.0996888, 37.3873134],
    ["별똥집", 127.0953796, 37.4020008],
    ["우리내 집", 127.0928823, 37.4032538],
    ["스킵플로어 하우스", 127.0960134, 37.4013944],
    ["ㄱㅁ주택", 127.0653488, 37.3909712],
    ["LIFE_FACTORY; 間", 27.0985008, 37.3931624],
    ["반석헌", 127.0984465, 37.3967737],
    ["오목한집", 127.0937487, 37.4023445],
    ["e블레시움 저에너지하우스", 127.0988041, 37.3920523],
    ["노란돌집", 127.0998281, 37.3958680],
    ["I-HOUSE", 127.0680296, 37.3899833],
    ["Odd Corner House", 127.0993932, 37.3966122],
    ["판교 House", 127.0997100, 37.3871263],
    ["미소(美疏) 드리움 하우스", 127.0852529, 37.3916670],
    ["판교동 주택", 127.0955813, 37.4023641],
    ["Casa de la jolla", 127.1008382, 37.3904504],
    ["판교50호", 127.0981919, 37.3869750],
    ["Easy House", 127.0835819, 37.3919843],
    ["Patio House", 127.0928589, 37.4025445],
    ["하이안", 127.0998748, 37.3936057],
    ["Parnell", 127.0986109, 37.4000847],
    ["Heavenly", 127.1097744, 37.3848043],
    ["Le Cube Blanc", 127.0801518, 37.3896270],
    ["X+HOUSE", 127.1002502, 37.3940235],
    ["P House", 127.0970995, 37.3995070],
    ["Wall House", 127.0998972, 37.3898607],
    ["Maison Ciel", 127.0982809, 37.4003743],
    ["큐브 하우스", 127.1003335, 37.3928601],
    ["캥거루하우스", 127.1091019, 37.3841129],
    ["N/A", 127.0969906, 37.4021302],
    ["N/A", 127.1008183, 37.3910086],
    ["N/A", 127.0960237, 37.4011918],
    ["영은재", 127.0987062, 37.3863811],
    ["Table Spoon", 127.0979191, 37.4001965],
    ["기운생동", 127.0809366, 37.3929428],
    ["P HOUSE", 127.0803223, 37.3918053],
    ["Scale-ing House", 127.0676278, 37.3902269],
    ["기숙사(奇淑思)", 127.0804511, 37.3891926],
    ["고동이네", 127.0939346, 37.4022237],
    ["손톱집", 127.0928153, 37.3985982],
    ["하늘집", 127.1001465, 37.3932175],
    ["The Float", 127.0994675, 37.3865389],
    ["파이림(π-林)", 127.0985923, 37.3964489],
    ["캥거루집", 127.0932903, 37.4033189],
    ["사각4각", 127.0932752, 37.4023079],
    ["공원집", 127.0822380, 37.3890807],
    ["7˚House", 127.0985880, 37.3868523],
    ["온유재", 127.0965122, 37.4025783],
    ["안단테 칸타빌레", 127.0676860, 37.3921859],
    ["가족의 꿈이 자라는 집", 127.0999027, 37.3873373],
    ["L.K. House", 127.1097823, 37.3851302],
    ["요철동(凹凸棟)", 127.0999998, 37.3940336],
    ["소소헌(蘇素軒)", 127.0807011, 37.3921704],
    ["N/A", 127.1000233, 37.3942232],
    ["에지하우스 Ⅱ", 127.0999777, 37.3954763],
    ["N/A", 127.0995391, 37.3958533],
    ["위가원", 127.0969160, 37.3981584],
    ["상현재", 127.0992699, 37.3867818],
    ["임소재", 127.0692066, 37.3893336],
    ["N/A", 127.0980022, 37.3873208],
    ["방연당", 127.0851121, 37.3912303],
    ["판교 s", 127.0980702, 37.3986601],
    ["키싱 에지 하우스", 127.0669356, 37.3902694],
    ["우정원", 127.0999701, 37.3861529],
    ["붉은벽돌집", 127.0817646, 37.3891272],
    ["Deep Blue House", 127.0821594, 37.3894322]
];

var map = new naver.maps.Map('map', {
    center: new naver.maps.LatLng(37.3950388, 127.084037),
    zoom: 10,
    zoomControl: true,
    zoomControlOptions: { //줌 컨트롤의 옵션
        position: naver.maps.Position.TOP_RIGHT
    }
});

function getClickHandler(marker, infoWindow) {
    return function(e) {
        if (infoWindow.getMap()) {
            infoWindow.close();
        } else {
            infoWindow.open(map, marker);
        }
    }
}

for (var i = 0; i <infos.length; i++) {

    var info = infos[i]

    var marker = new naver.maps.Marker({
        position: new naver.maps.LatLng(info[2], info[1]),
        map: map
    });

    var infoWindow = new naver.maps.InfoWindow({
        content: '<div style="text-align:center;padding:5px;">' + info[0] + '</div>'
    });

    naver.maps.Event.addListener(marker, 'click', getClickHandler(marker, infoWindow));
}

</script>

| 이름  | 설계  | 시공   | 구조  | 듀플렉스 | 링크 |
| - | - | - | - | :-: | - |
| <!--판교로 197번길 8-2-->[온당](http://naver.me/FbQUMDp2){:target="_blank"} | [ofaa][001]{:target="_blank"} | 이든하임 | 경량목 | Y | [전원속의 내집][001_1]{:target="_blank"}, [한국일보][001_2]{:target="_blank"}  |
| <!--서판교로 188번길 11-->[소소원](http://naver.me/xVHc8rcA){:target="_blank"} | [구가도시][002]{:target="_blank"} | [스튜가][002_1]{:target="_blank"} | 경량목 | N | [전원속의 내집][002_2]{:target="_blank"} |
| <!--판교로 198번길 3-9-->[함양재](http://naver.me/5LUhqGgS){:target="_blank"} | [구가도시][003]{:target="_blank"} |  |  | N | [시사인][003_1]{:target="_blank"} |
| <!--서판교로 108번길 12-->[무이동](http://naver.me/F1lYWfAl){:target="_blank"} | [조성욱건축사사무소][004]{:target="_blank"} | 하오스 | RC | Y | [전원속의 내집][004_1]{:target="_blank"} |
| <!--서판교로 132번길 15-12-->[AD Fontes](http://naver.me/FujneaRp){:target="_blank"} | [TRU Architects][005]{:target="_blank"} | [de Archiis][005_1]{:target="_blank"} | RC | N | [리빙센스][005_2]{:target="_blank"} |
| <!--서판교로 180번길 9-->[동/서안재](http://naver.me/GGmZHkZG){:target="_blank"} | [호멘토][006]{:target="_blank"} | [호멘토][006]{:target="_blank"} | 경량목 | Y | [전원속의 내집][006_1]{:target="_blank"} |
| <!--판교로 210번길 4-1-->[시전당](http://naver.me/5U7yAgNz){:target="_blank"} | [JHY건축사무소][007]{:target="_blank"} |  | RC | N | [homify][007_1]{:target="_blank"} |
| <!--판교로 210번길 18-4-->[One Roof House](http://naver.me/Fpz2uwMs){:target="_blank"} | [MLNP Architects][008]{:target="_blank"} | [GIP][008_1]{:target="_blank"} | 경량목 | N | [homify][008_2]{:target="_blank"}, [동영상][008_3]{:target="_blank"}, [전원속의 내집][008_4]{:target="_blank"}|
| <!--판교로 197번길 3-10-->[층층마루집](http://naver.me/GoVMCwsP){:target="_blank"} | [조진만건축사무소][009]{:target="_blank"} |  | RC | N | [월간공간][009_1]{:target="_blank"} |
| <!--서판교로 180번길 3-3-->[호연당](http://naver.me/IM3gCENM){:target="_blank"} | [ATELIER17][010]{:target="_blank"} | 서강건설주식회사 | RC | N | [homify][010_1]{:target="_blank"} |
| <!--판교로 197번길 19-->[삼대헌](http://naver.me/xZ2LBXeK){:target="_blank"} | [ISM건축][011]{:target="_blank"} | | | N | [리빙센스][011_1]{:target="_blank"} |
| <!--서판교로 32번길 24-->[TIMBER DUPLEX 1](http://naver.me/5shzlPnV){:target="_blank"} | [민워크샵][012]{:target="_blank"} | [스튜가][002_1]{:target="_blank"} | 중량목 | Y | [homify][012_1]{:target="_blank"} |
| <!--운중로 14번길 51-->[POP House](http://naver.me/xUKQ6aLV){:target="_blank"} | [AnLStudio][013]{:target="_blank"} | 이든하임 | 경량목 | Y | [전원속의 내집][013_1]{:target="_blank"} |
| <!--서판교로 100번길 4-14-->[이보재](http://naver.me/F9tF7ANo){:target="_blank"} | [KDDH][014]{:target="_blank"} | [하우징플러스][014_1]{:target="_blank"} | 경량목 | N | [전원속의 내집][014_2]{:target="_blank"} |
| <!--판교원로 311번길 16-9-->[HESED](http://naver.me/5k8cmtRh){:target="_blank"} | | | 경량목 | Y | [우먼센스][015_1]{:target="_blank"}, [건축주 블로그][015_2]{:target="_blank"} |
| <!--서판교로 74번길 10-->[동행](http://naver.me/FjkeU3uK){:target="_blank"} | [블루하우스코리아][016]{:target="_blank"} | [블루하우스코리아][016]{:target="_blank"} | 중량목 | Y | [리빙센스][016_1] |
| <!--서판교로 74번길 6-->[사이집](http://naver.me/Gx40C7ZN){:target="_blank"} | [조성욱건축사사무소][017]{:target="_blank"} | [JArchiv][017_1]{:target="_blank"} | RC | Y | [블로그][017_2]{:target="_blank"}, [페이스북][017_3]{:target="_blank"} |
| <!--판교원로 30번길 4-->[도시채](http://naver.me/G66MLu3z){:target="_blank"} | [유타건축][018]{:target="_blank"} | JAIN | 경량목 | Y | [전원속의 내집][018_1]{:target="_blank"} |
| <!--판교원로 299번길 3-->[흰벽돌집](http://naver.me/xhkfLBLS){:target="_blank"} | [건축사무소 공감][019]{:target="_blank"} | | RC | N | [전원속의 내집][019_1]{:target="_blank"} |
| <!--산운로 32번길 30-->[계수나무집](http://naver.me/xyhi1ycJ){:target="_blank"} | [솔토지빈건축사사무소][020]{:target="_blank"} | S5 | 경량목 | N | [동아일보][020_1]{:target="_blank"}, [월간Space][020_2]{:target="_blank"} |
| <!--서판교로 118번길 7-->[IZIP](http://naver.me/FD5fUub7){:target="_blank"} | [이재하건축사사무소][021]{:target="_blank"} | | RC | N | [CASA][021_1]{:target="_blank"}, [조선일보][021_2]{:target="_blank"} |
| <!--판교원로 299번길 6-5-->[YELLOW WOOD HOUSE](http://naver.me/5eqjvHly){:target="_blank"} | [이진욱건축사사무소][022]{:target="_blank"} | 효상건설 | RC | N | [블로그][022_2]{:target="_blank"}, [건축명장][022_1]{:target="_blank"} |
| <!--서판교로 180번길 18-5-->[별똥집](http://naver.me/5DUa69vy){:target="_blank"} | [SIE][023]{:target="_blank"} | | RC | N | [리빙센스][023_1]{:target="_blank"}, [월간Space][023_2]{:target="_blank"} |
| <!--판교로 209번길 49-3-->[우리내 집](http://naver.me/x6lrKdzM){:target="_blank"} | [아이디어5 건축사사무소][024]{:target="_blank"} | [스튜가][002_1]{:target="_blank"} | 경량목 | N | [전원주택라이프][024_1]{:target="_blank"}, [동영상][024_2]{:target="_blank"}, [건축명장][024_3]{:target="_blank"} |
| <!--판교로 197번길 7-->[스킵플로어 하우스](http://naver.me/5KeBp0Xw){:target="_blank"} | [마고퍼스][025]{:target="_blank"} | [마고퍼스][025]{:target="_blank"} | 경량목 | N | [전원속의 내집][025_1]{:target="_blank"} |
| <!--운중로 14번길 5-5-->[ㄱㅁ주택](http://naver.me/GCRzBCSg){:target="_blank"} | [와이즈건축][026]{:target="_blank"} | [JArchiv][026_2]{:target="_blank"} | RC | N | [전원속의 내집][026_1]{:target="_blank"} |
| <!--서판교로 66번길 3-3-->[LIFE_FACTORY; 間](http://naver.me/FXgWqef4){:target="_blank"} | [남기봉건축사사무소][027]{:target="_blank"} | 사람중심 | RC | N | [건설경제신문][027_1]{:target="_blank"} |
| <!--서판교로 108번길 3-6-->[반석헌](http://naver.me/FaxGoySu){:target="_blank"} | [조성욱건축사사무소][028]{:target="_blank"} | [마고퍼스][028_1]{:target="_blank"} | RC | Y | [리빙센스][028_2]{:target="_blank"} |
| <!--서판교로 188번길 10-->[오목한집](http://naver.me/5iAOCdOe){:target="_blank"} | [민워크샵][029]{:target="_blank"} | | RC | Y | [월간Space][029_1]{:target="_blank"} |
| <!--서판교로 58번길 7-->[e블레시움 저에너지하우스](http://naver.me/GVspxkCA){:target="_blank"} | [노드플랜][030]{:target="_blank"} | [풍산우드홈][030_1]{:target="_blank"} | 경량목 | N | [건축명장][030_2]{:target="_blank"}, [행복이 가득한집][030_3]{:target="_blank"} |
| <!--서판교로 100번길 16-->[노란돌집](http://naver.me/50kUCI8G){:target="_blank"} | [SIE][031]{:target="_blank"} | | RC | N | [이코노믹리뷰][031_1]{:target="_blank"} |
| <!--판교원로 16번길 3-->[I-HOUSE](http://naver.me/FNPUTsd0){:target="_blank"} | [SIE][032]{:target="_blank"} | 사람중심 | RC | N | [전원속의 내집][032_1]{:target="_blank"} |
| <!--서판교로 108번길 14-->[Odd Corner House](http://naver.me/G8dcBxmE){:target="_blank"} | [민워크샵][033]{:target="_blank"} | [JArchiv][033_2]{:target="_blank"} | RC | N | [CASA][033_1]{:target="_blank"} |
| <!--판교원로 299번길 6-6-->[판교 House](http://naver.me/FI02dQ9y){:target="_blank"} | [JYA-rchitects][034]{:target="_blank"} | 위빌 | RC | Y | [ArchDaily][034_1]{:target="_blank"} |
| <!--운중로197번길 9-->[미소(美疏) 드리움 하우스](http://naver.me/GBV1Jr4J){:target="_blank"} | [블루하우스코리아][016]{:target="_blank"} | [블루하우스코리아][016]{:target="_blank"} | 중량목 | N | [전원속의 내집][035_1]{:target="_blank"} |
| <!--판교로 197번길 18-->[판교동 주택](http://naver.me/5YYO9sMZ){:target="_blank"} | [스페이스목금토][036]{:target="_blank"} | 모비덤 | RC | N | [전원속의 내집][036_1]{:target="_blank"} |
| <!--서판교로 44번길 18-15-->[Casa de la jolla](http://naver.me/GSvPSbtC){:target="_blank"} | [정재헌 건축가][037]{:target="_blank"} | | RC, 경량목 | N | [전원속의 내집][037_1]{:target="_blank"} |
| <!--판교원로 287번길 4-6-->[판교50호](http://naver.me/G9jxFakr){:target="_blank"} | [이집소][038]{:target="_blank"} | 이든하우스 | 경량목 | Y | [전원속의 내집][038_1]{:target="_blank"} |
| <!--산운로 208번길 10-3-->[Easy House](http://naver.me/GTYRUEMj){:target="_blank"} | [TRU Architects][039]{:target="_blank"} | 나래건설 | RC | N | [전원속의 내집][039_1]{:target="_blank"} |
| <!--서판교로 188-->[Patio House](http://naver.me/x0KA9VAH){:target="_blank"} | [바우건축][040]{:target="_blank"} | 이오디자인 | RC | N | [전원속의 내집][040_1]{:target="_blank"} |
| <!--서판교로 74번길 13-->[하이안](http://naver.me/FBRF4TYE){:target="_blank"} | [건인 E&C][041]{:target="_blank"} | 르마누아 | RC | N | [리빙센스][041_1]{:target="_blank"} |
| <!--판교로210번길 16-->[Parnell](http://naver.me/xSmtwio3){:target="_blank"} | [de Archiis][042]{:target="_blank"} | [de Archiis][042]{:target="_blank"} | RC | N | [CASA][042_1]{:target="_blank"} |
| <!--판교역로 28번길 10-->[Heavenly](http://naver.me/xaG4IbCz){:target="_blank"} | [이재하건축사사무소][043]{:target="_blank"} | [JArchiv][043_2]{:target="_blank"} | RC | N | [CASA][043_1]{:target="_blank"} |
| <!--운중로 166번길 20-11-->[Le Cube Blanc](http://naver.me/5t5GQavj){:target="_blank"} | 이순조, 이경은 |  [JArchiv][044_2]{:target="_blank"} | RC | N | [CASA][044_1]{:target="_blank"} |
| <!--판교로 210번길 88-->[X+HOUSE](http://naver.me/GcIJlfn4){:target="_blank"} | 마추건축 | 호수건설 | RC | N | [주택저널][045_1]{:target="_blank"} |
| <!--서판교로 132번길 15-7-->[P House](http://naver.me/5oF9dMbr){:target="_blank"} | [유토포건축사사무소][046]{:target="_blank"} | [이안알앤씨][046_1]{:target="_blank"} | RC | Y | [주택저널][046_2]{:target="_blank"} |
| <!--서판교로32번길 19-6-->[Wall House](http://naver.me/5PfMePIj){:target="_blank"} | [운생동][047]{:target="_blank"} | 리원건설 | RC | N | [행복이 가득한집][047_1]{:target="_blank"}, [월간Space][047_2]{:target="_blank"}  |
| <!--판교로 210번길 12-2-->[Maison Ciel](http://naver.me/5aB5KGax){:target="_blank"} | [ISM건축][048]{:target="_blank"} | | RC | N | [행복이 가득한집][048_1]{:target="_blank"} |
| <!--서판교로 66번길 19-->[큐브 하우스](http://naver.me/5k8cmFJu){:target="_blank"} | [경영위치][049]{:target="_blank"} | | RC | N | [행복이 가득한집][049_1]{:target="_blank"},[월간Space][049_2]{:target="_blank"} |
| <!--판교역로 34-->[캥거루하우스](http://naver.me/IDh0dL1a){:target="_blank"} | [유현준건축사사무소][050]{:target="_blank"} | 삼대건설 | RC | N | [월간Space][050_1]{:target="_blank"} |
| <!--판교로209번길 9-->[지도](http://naver.me/GBV1Jwa3){:target="_blank"} | [예주홈플랜][051]{:target="_blank"} | [예주홈플랜][051]{:target="_blank"} | 경량목 | N | [전원속의 내집][051_1]{:target="_blank"} |
| <!--서판교로 44번길 29-3-->[map](http://naver.me/FQlq2HUb){:target="_blank"} | [타니가와][052]{:target="_blank"} | [타니가와][052]{:target="_blank"} | 경량목 | N | [전원속의 내집][052_1]{:target="_blank"} |
| <!--판교로 197번길 3-6-->[map](http://naver.me/Gv0pVmkY){:target="_blank"} | [타니가와][053]{:target="_blank"} | [타니가와][053]{:target="_blank"} | 중량목 | N | [전원속의 내집][053_1]{:target="_blank"} |
| <!--판교원로 286번길 37-->[영은재](http://naver.me/xkfwbaJ2){:target="_blank"} | [de Archiis][054]{:target="_blank"} | [de Archiis][054]{:target="_blank"} | RC | N | [CASA][054_1]{:target="_blank"} |
| <!--판교로 210번길 12-8-->[Table Spoon](http://naver.me/Glq1gkPn){:target="_blank"} | [de Archiis][055]{:target="_blank"} | [de Archiis][055]{:target="_blank"} | RC | N | [CASA][055_1]{:target="_blank"} |
| <!--산운로 170번길 3-1-->[기운생동](http://naver.me/FzGu50u3){:target="_blank"} | [경영위치][056]{:target="_blank"} | [이안알앤씨][056_1]{:target="_blank"}  | RC | N | [전원주택 라이프][056_2]{:target="_blank"} |
| <!--산운로 208번길 39-->[P HOUSE](http://naver.me/5KeBpxrn){:target="_blank"} | EAST4 | | RC | N | [월간Space][057_1]{:target="_blank"}, [MasilWIDE][057_2]{:target="_blank"} |
| <!--판교원로 14번길 2-->[Scale-ing House](http://naver.me/G9jxFIZA){:target="_blank"} | [조호건축][058]{:target="_blank"} | | RC | N | [homify][058_1]{:target="_blank"}, [블로그][058_2]{:target="_blank"} |
| <!--운중로 166번길 20-26-->[기숙사(奇淑思)](http://naver.me/xUKQ6CHc){:target="_blank"} | [유타건축][059]{:target="_blank"} | [시스홈 씨엔엘][059_1]{:target="_blank"} | 경량목 | N | [리빙센스][059_2]{:target="_blank"} |
| <!--서판교로 188번길 12-1-->[고동이네](http://naver.me/xqrF2koF){:target="_blank"} | [솔토지빈건축사사무소][060]{:target="_blank"} | [시스홈 씨엔엘][060_1]{:target="_blank"} | 경량목 | Y | [건축명장][060_2]{:target="_blank"}, [건축주 블로그][060_3]{:target="_blank"} | 
| <!--판교로 156번길 4-2-->[손톱집](http://naver.me/xqrF2ksx){:target="_blank"} | [경영위치][061]{:target="_blank"} | [이안알앤씨][061_1]{:target="_blank"} | RC | N | [월간Space][061_2]{:target="_blank"} |
| <!--서판교로 66번길 13-7-->[하늘집](http://naver.me/x7Tqw9Lk){:target="_blank"} | [SIE][062]{:target="_blank"} | 나래건설 | RC | N | [시사인][062_1]{:target="_blank"}, [블로그][062_2]{:target="_blank"} |
| <!--판교원로 303-->[The Float](http://naver.me/xTx2Mwvt){:target="_blank"} | [조성욱건축사사무소][063]{:target="_blank"} | [JArchiv][063_3]{:target="_blank"} | RC | Y | [매일경제][063_1]{:target="_blank"}, [건축명장][063_2]{:target="_blank"} |
| <!--서판교로 108번길 6-->[파이림(π-林)](http://naver.me/GE2GzgKm){:target="_blank"} | [조성욱건축사사무소][064]{:target="_blank"} | [JArchiv][064_2]{:target="_blank"} | RC | Y | [리빙센스][064_1]{:target="_blank"} |
| <!--판교로 209번길 47-->[캥거루집](http://naver.me/G4AbFaYT){:target="_blank"} | [디자인초록][065]{:target="_blank"} | [준성건축][065_1]{:target="_blank"} | RC | Y | [리빙센스][065_2]{:target="_blank"} |
| <!--서판교로 180번길 3-8-->[사각4각](http://naver.me/xG5q8Z46){:target="_blank"} | [가와건축사사무소][066]{:target="_blank"} | 에제르 건설 | RC, 경량목 | N | [월간Space][066_1]{:target="_blank"} |
| <!--운중로 166번길 27-12-->[공원집](http://naver.me/G4AbFiet){:target="_blank"} | [정재헌 건축가][067]{:target="_blank"} | | RC | N | [월간Space][067_1]{:target="_blank"} |
| <!--판교원로 295-->[7˚House](http://naver.me/xIE4yzeh){:target="_blank"} | 권혁천 | | | N | [CASA][068_1]{:target="_blank"}, [행복이 가득한집][068_2]{:target="_blank"} |
| <!--판교로 209번길 15-->[온유재](http://naver.me/GM6KIqej){:target="_blank"} | [건축사사무소 공장][069]{:target="_blank"} | | RC | N | [건설경제신문][069_1]{:target="_blank"} |
| <!--산운로 56번길 4-->[안단테 칸타빌레](http://naver.me/GbmdWbix){:target="_blank"} | [유하우스][070]{:target="_blank"} | [유하우스][070]{:target="_blank"} | RC | N | [건설경제신문][070_1]{:target="_blank"} |
| <!--판교원로 311번길 15-->[가족의 꿈이 자라는 집](http://naver.me/GmwjmeeH){:target="_blank"} | [토우재][071]{:target="_blank"} | | RC | N | [주택저널][071_1]{:target="_blank"} |
| <!--판교역로 28번길 14-->[L.K. House](http://naver.me/xo2z3xRa){:target="_blank"} | [토우재][071]{:target="_blank"} | (주)예성인 | RC | N | [주택저널][072_1]{:target="_blank"} |
| <!--판교로 210번길 88-4-->[요철동(凹凸棟)](http://naver.me/FjketeKX){:target="_blank"} | [정재헌 건축가][067]{:target="_blank"} | | RC | N | [이코노믹리뷰][073_1]{:target="_blank"}, [건축도시정보센터][073_2]{:target="_blank"} |
| <!--산운로 170번길 11-->[소소헌(蘇素軒)](http://naver.me/Fs5GmOq1){:target="_blank"} | [UTOLabs][074]{:target="_blank"} | [C&O건설][074_1]{:target="_blank"} | RC | N | [MasilWIDE][074_2]{:target="_blank"}, [월간Space][074_3]{:target="_blank"} |
| <!--판교로 210번길 84-3-->[map](http://naver.me/GRY2swZs){:target="_blank"} | [이재하건축사사무소][075]{:target="_blank"} | | RC | N | [월간Space][075_1]{:target="_blank"} |
| <!--서판교로 100번길 4-18-->[에지하우스 Ⅱ](http://naver.me/5oF9Nebj){:target="_blank"} | [ISM건축][076]{:target="_blank"} | [다산건설엔지니어링][076_1]{:target="_blank"} | RC | N | [월간Space][076_2]{:target="_blank"} |
| <!--서판교로 100번길 12-->[map](http://naver.me/5OxIN8Rg){:target="_blank"} | [이재하건축사사무소][077]{:target="_blank"} | | RC | N | [블로그][077_1]{:target="_blank"} |
| <!--서판교로 126번길 3-5-->[위가원](http://naver.me/FE8aFqiu){:target="_blank"} | [이재하건축사사무소][078]{:target="_blank"} | | RC | N | [CASA][078_1]{:target="_blank"} |
| <!--판교원로 299번길 2-->[상현재](http://naver.me/IDh0PtQU){:target="_blank"} | [이재하건축사사무소][079]{:target="_blank"} | | RC | N | [월간웨딩21][079_1]{:target="_blank"} |
| <!--운중로 14번길 49-->[임소재](http://naver.me/5pxmbf4W){:target="_blank"} | [조성욱건축사사무소][080]{:target="_blank"} |  [JArchiv][080_1]{:target="_blank"} | RC | Y | |
| <!--서판교로 6번길 6-->[map](http://naver.me/GVsp6zQ2){:target="_blank"} | [이손건축][081]{:target="_blank"} | [JArchiv][081_1]{:target="_blank"} | RC | N | [건축명장][081_2]{:target="_blank"} |
| <!--운중로 197번길 3-->[방연당](http://naver.me/FTFv6Bsz){:target="_blank"} | [버텍스 디자인][082]{:target="_blank"} | [de Archiis](082_1){:target="_blank"} | RC | N | [행복이 가득한 집](082_2){:target="_blank"} |
| <!--서판교로 126번길 13-4-->[판교 s](http://naver.me/IgBd6fd1){:target="_blank"} | [구가도시](083){:target="_blank"} | [JArchiv][083_1]{:target="_blank"} | RC | Y | [한겨레][083_2]{:target="_blank"} |
| <!--운중로 14번길 19-12-->[키싱 에지 하우스](http://naver.me/GLrdqaIv){:target="_blank"} | [민워크샵][084]{:target="_blank"} | [스튜가][002_1]{:target="_blank"} | 경량목 | Y | [리빙센스][084_1]{:target="_blank"}, [동영상][084_2]{:target="_blank"} | 
| <!--판교원로 311번길 1-->[우정원](http://naver.me/xr1b2jkg){:target="_blank"} | [타니가와][085]{:target="_blank"} | [타니가와][085]{:target="_blank"} | 경량목 | N | [주택저널][085_1]{:target="_blank"} |
| <!--운중로 166번길 27-16-->[붉은벽돌집](http://naver.me/5lbmuDtK){:target="_blank"} | [SIE][086]{:target="_blank"} | | | N | [동아일보][086_1]{:target="_blank"} |
| <!--운중로 166번길 19-9-->[Deep Blue House](http://naver.me/FBRsQVGL){:target="_blank"} | [이진욱건축사사무소][087]{:target="_blank"} | | RC | N | [리빙센스][087_1]{:target="_blank"} |


[087]: http://leenhwang.com/archives/portfolio/판교_팝업
[087_1]: http://navercast.naver.com/magazine_contents.nhn?rid=1094&contents_id=82353

[086]: http://www.sie-jungsujin.com/p/portfolio_page/red-brick-house%EB%B6%89%EC%9D%80%EB%B2%BD%EB%8F%8C%EC%A7%91/
[086_1]: http://news.naver.com/main/read.nhn?mode=LSD&mid=sec&sid1=103&oid=020&aid=0002487052

[085]: http://tg-k.co.kr/publicity/ad_read.asp?cidx=163
[085_1]: http://www.jutek.kr/user/selectBbsColumn.do?BBS_NUM=5638

[084]: http://www.minworkshop.com/index.php?/kissing-edge/
[084_1]: http://navercast.naver.com/magazine_contents.nhn?rid=1094&contents_id=105662
[084_2]: https://www.youtube.com/watch?v=ZsW1F1rorpA

[083]: http://www.guga.co.kr/
[083_1]: http://www.jarchiv.com/bbs/board.php?bo_table=portfolio&wr_id=69&page=0&page=0
[083_2]: http://www.hani.co.kr/arti/specialsection/esc_section/623859.html

[082]: http://ver-tex.net/?page_id=4509
[082_1]: http://www.dearchiis.co.kr/bbs/board.php?bo_table=projects&wr_id=10
[082_2]: http://happy.designhouse.co.kr/magazine/magazine_view?info_id=50771

[081]: https://www.isonarch.com/
[081_1]: http://www.jarchiv.com/bbs/board.php?bo_table=portfolio&wr_id=95&page=0&page=0
[081_2]: http://masterbuilder.kr/portfolio/%ED%8C%90%EA%B5%90%EC%A3%BC%ED%83%9D/

[080]: http://www.johsungwook.com/index.php?/projects/unjung-ns-house/
[080_1]: http://www.jarchiv.com/bbs/board.php?bo_table=portfolio&wr_id=78/3660031334_TgQe42oj_01.jpg

[079]: http://www.leejaeha.com/work/work11.html
[079_1]: http://www.wef.co.kr/bbs/board.php?bo_table=life&wr_id=79518

[078]: http://www.leejaeha.com/work/works2011-6.html
[078_1]: http://navercast.naver.com/magazine_contents.nhn?rid=1409&contents_id=16979

[077]: http://www.leejaeha.com/work/works2012-3.html
[077_1]: http://fottec.com/220071282273

[076]: http://ism-architects.com/?fluxus_portfolio=edge-house-ii
[076_1]: http://blog.naver.com/dasan_ce/220615281190
[076_2]: http://www.vmspace.com/2008_re/kor/sub_emagazine_view.asp?category=architecture&idx=12215&pageNum=1

[075]: http://www.leejaeha.com/work/works2013-3.html
[075_1]: http://masilwide.com/pangyo-leejaeha-architects/

[074]: http://utolabs.com/xe/index.php?mid=projects&category=408
[074_1]: http://www.cnoenc.com/projects.html
[074_2]: http://masilwide.com/white-house蘇素軒-utolabs/
[074_3]: http://www.vmspace.com/2008_re/kor/sub_emagazine_view.asp?category=architecture&idx=11886&pageNum=1

[073_1]: http://www.econovill.com/archives/82451
[073_2]: http://www.aurum.re.kr/Bits/BuildingDoc.aspx?num=2506#.WJlPXLaLSl4

[072_1]: http://www.jutek.kr/user/selectBbsColumn.do?BBS_NUM=287&COD03_CODE=c0301&MEN02_NUM=28&pageNum=8

[071]: http://www.towoojae.com/bbs/board.php?bo_table=works5
[071_1]: http://www.jutek.kr/user/selectBbsColumn.do?BBS_NUM=358&COD03_CODE=c0301&MEN02_NUM=28&pageNum=7

[070]: http://blog.naver.com/u-haus/220600917879
[070_1]: http://www.cnews.co.kr/uhtml/read.jsp?idxno=201504131120497960175

[069]: http://gjarch.com/index.php/time/-/2/
[069_1]: http://www.cnews.co.kr/uhtml/read.jsp?idxno=201612021553560190404

[068_1]: http://www.casa.co.kr/brand/contents/view.do?articleNo=6105&schCd=0101070107
[068_2]: http://happy.designhouse.co.kr/magazine/magazine_view?info_id=61082

[067]: http://www.jeongjaeheon.com/
[067_1]: http://www.vmspace.com/2008_re/kor/sub_emagazine_view.asp?category=architecture&idx=11958&pageNum=13

[066]: http://kawadesign.net/wp/portfolio/2120/
[066_1]: http://www.vmspace.com/2008_re/kor/sub_emagazine_view.asp?category=architecture&idx=12201&pageNum=1

[065]: http://blog.naver.com/want38
[065_1]: http://www.jscons.co.kr/bbs/board.php?bo_table=menu3_02&wr_id=11
[065_2]: http://navercast.naver.com/magazine_contents.nhn?rid=1094&contents_id=126499

[064]: http://www.johsungwook.com/index.php?/projects/pangyo-superduplex/
[064_1]: http://www.smlounge.co.kr/living/article/33199
[064_2]: http://www.jarchiv.com/bbs/board.php?bo_table=portfolio&wr_id=96&page=0&page=0

[063]: http://www.johsungwook.com/index.php?/projects/pangyodong-residence-645-8/
[063_1]: http://news.naver.com/main/read.nhn?mode=LSD&mid=sec&sid1=101&oid=009&aid=0003772083
[063_2]: http://masterbuilder.kr/portfolio/더-플로트/
[063_3]: http://www.jarchiv.com/bbs/board.php?bo_table=portfolio&wr_id=92&page=0&page=0

[062]: http://www.sie-jungsujin.com/p/portfolio_page/spring-house하늘집/
[062_1]: http://news.naver.com/main/read.nhn?mode=LSD&mid=sec&sid1=102&oid=308&aid=0000008582
[062_2]: http://my5chul.blog.me/60150453393

[061]: http://kywc.com/portfolio/pangyo-h-residence/
[061_1]: http://www.eanrnc.com
[061_2]: http://www.vmspace.com/2008_re/kor/sub_emagazine_view.asp?category=architecture&idx=11803

[060]: http://soltos.kr
[060_1]: http://hausstyle.co.kr/wp/주-시스홈씨엔엘
[060_2]: http://masterbuilder.kr/portfolio/판교동-단독주택/
[060_3]: http://godong.tistory.com/category/집짓기/%5B2014%5D판교고동이네

[059]: http://www.utaa.co.kr/works.html?year=2016&idx=119&
[059_1]: https://story.kakao.com/ch/syshome/F9AutfYl4b0
[059_2]: http://navercast.naver.com/magazine_contents.nhn?rid=1094&contents_id=127763

[058]: http://johoarchitecture.com
[058_1]: https://www.homify.co.kr/ideabooks/33096/homify360˚-:-아이디어가-돋보이는-집,-판교-스케일링-하우스
[058_2]: http://danyulkim.blog.me/220152174060

[057_1]: http://www.vmspace.com/2008_re/kor/sub_emagazine_view.asp?category=architecture&idx=11462&pageNum=1
[057_2]: http://masilwide.com/p-house/

[056]: http://kywc.com/portfolio/pangyo-l-residence/
[056_1]: http://www.eanrnc.com
[056_2]: http://m.post.naver.com/viewer/postView.nhn?volumeNo=5265815&memberNo=24659848&vType=VERTICAL

[055]: http://www.dearchiis.co.kr/bbs/board.php?bo_table=projects&wr_id=87
[055_1]: http://navercast.naver.com/magazine_contents.nhn?rid=1409&contents_id=109715

[054]: http://www.dearchiis.co.kr/bbs/board.php?bo_table=projects&wr_id=73
[054_1]: http://navercast.naver.com/magazine_contents.nhn?rid=1409&contents_id=54646

[053]: http://tg-k.co.kr/showroom/modelhouse_view_korea_pangyo9.asp#ad-image-0
[053_1]: http://navercast.naver.com/magazine_contents.nhn?rid=1433&contents_id=118449

[052]: http://tg-k.co.kr/showroom/modelhouse_view_korea_pangyo3.asp#ad-image-9
[052_1]: http://navercast.naver.com/magazine_contents.nhn?rid=1433&contents_id=27064

[051]: http://www.yejuhomeplan.com/bbs/bbs/board.php?bo_table=contractors_all1&wr_id=41&sca=6070
[051_1]: http://www.uujj.co.kr/bbs/board.php?bo_table=house&wr_id=62&sfl=wr_subject%7C%7Cwr_content&stx=판교&sop=and&page=2

[050]: http://www.hyunjoonyoo.com/projects/projects01.php
[050_1]: http://www.vmspace.com/2008_re/kor/sub_emagazine_view.asp?category=architecture&idx=12002

[049]: http://kywc.com/portfolio/pangyo-y-residence/
[049_1]: http://happy.designhouse.co.kr/magazine/magazine_view?info_id=56335
[049_2]: http://www.vmspace.com/2008_re/kor/sub_emagazine_view.asp?category=people&idx=11682

[048]: http://ism-architects.com/?fluxus_portfolio=maison-ciel
[048_1]: http://happy.designhouse.co.kr/magazine/magazine_view?info_id=69499

[047]: http://www.usdspace.com/
[047_1]: http://happy.designhouse.co.kr/magazine/magazine_view?info_id=75991
[047_2]: http://www.vmspace.com/2008_re/kor/sub_emagazine_view.asp?category=architecture&idx=12169

[046]: http://www.urbantopo.com/projects/architecture/p-house
[046_1]: http://www.eanrnc.com/index.php?mid=works&category=431514#?mid=works&category=431514&document_srl=432942
[046_2]: http://www.jutek.kr/user/selectBbsColumn.do?BBS_NUM=555&COD03_CODE=c0301&MEN02_NUM=28

[045_1]: http://www.jutek.kr/user/selectBbsColumn.do?BBS_NUM=6891&COD03_CODE=c0301&MEN02_NUM=28

[044_1]: http://www.casa.co.kr/brand/contents/view.do?articleNo=7466&pg=13&schCd=0101070101&depth=2
[044_2]: http://www.jarchiv.com/bbs/board.php?bo_table=portfolio&wr_id=64&page=0&page=0

[043]: http://www.leejaeha.com/work/works2013-1.html
[043_1]: http://navercast.naver.com/magazine_contents.nhn?rid=1409&contents_id=54618
[043_2]: http://www.jarchiv.com/bbs/board.php?bo_table=portfolio&wr_id=72&page=0&page=0

[042]: http://www.dearchiis.co.kr/bbs/board.php?bo_table=projects&wr_id=83
[042_1]: http://navercast.naver.com/magazine_contents.nhn?rid=1409&contents_id=83525

[041]: http://www.kunin.co.kr/kunin/bbs/bbs/board.php?bo_table=architecture&wr_id=36&sca=&plimg=30680842_oDclCyPt_008.jpg
[041_1]: http://navercast.naver.com/magazine_contents.nhn?rid=1094&rid=&contents_id=66483

[040]: http://www.bauarchitects.com/index.php?/architecture/patio-house-l/
[040_1]: http://navercast.naver.com/magazine_contents.nhn?rid=1433&contents_id=36794

[039]: http://www.trugroup.co.kr/easyhouse
[039_1]: http://navercast.naver.com/magazine_contents.nhn?rid=1433&contents_id=49797

[038]: http://cafe.naver.com/duplexhome
[038_1]: http://navercast.naver.com/magazine_contents.nhn?rid=1433&contents_id=85039

[037]: http://www.jeongjaeheon.com
[037_1]: http://navercast.naver.com/magazine_contents.nhn?rid=1433&contents_id=103202

[036]: http://www.spacemgt.co.kr
[036_1]: http://navercast.naver.com/magazine_contents.nhn?rid=1433&contents_id=87413

[035_1]: http://navercast.naver.com/magazine_contents.nhn?rid=1433&contents_id=122278

[034]: http://jyarchitects.com/708
[034_1]: http://www.archdaily.com/781435/pangyo-house-jya-rchitects

[033]: http://www.minworkshop.com/index.php?/odd-corner/
[033_1]: http://navercast.naver.com/magazine_contents.nhn?rid=1409&contents_id=18430
[033_2]: http://www.jarchiv.com/bbs/board.php?bo_table=portfolio&wr_id=65&page=0&page=0

[032]: http://www.sie-jungsujin.com/p/portfolio_page/i-house이-집-ver02/
[032_1]: http://navercast.naver.com/magazine_contents.nhn?rid=1433&contents_id=108161

[031]: http://www.sie-jungsujin.com/p/portfolio_page/yellow-stone-house노란돌집/
[031_1]: http://www.econovill.com/archives/42585

[030]: http://www.nodeplan.com/?sd=2&sc=2_1_2&gyear=2014&wnum=109&page=1
[030_1]: http://www.woodhomes.co.kr/bbs/board.php?bo_table=04_000_06&wr_id=1
[030_2]: http://masterbuilder.kr/portfolio/e블레시움-판교-저에너지하우스/
[030_3]: http://happy.designhouse.co.kr/magazine/magazine_view?info_id=68955

[029]: http://www.minworkshop.com/index.php?/sunlight-house/
[029_1]: http://www.vmspace.com/2008_re/kor/sub_emagazine_view.asp?category=architecture&idx=11985&pageNum=1

[028]: http://www.johsungwook.com/index.php?/projects/bundanggu-pangyodong-residence/
[028_1]: http://www.magopus.co.kr/main.php
[028_2]: http://www.smlounge.co.kr/living/article/20728

[027]: http://www.life-factory.co.kr/
[027_1]: http://www.cnews.co.kr/uhtml/read.jsp?idxno=201612161106284140538

[026]: http://wisearchitecture.com/index.php/projects/km/
[026_1]: http://navercast.naver.com/magazine_contents.nhn?rid=1433&contents_id=57867
[026_2]: http://www.jarchiv.com/bbs/board.php?bo_table=portfolio&wr_id=68&page=0&page=0

[025]: http://www.magopus.co.kr/bbs/board.php?bo_table=ex&wr_id=176
[025_1]: http://navercast.naver.com/magazine_contents.nhn?rid=1433&contents_id=70594

[024]: http://blog.daum.net/kyr824/584
[024_1]: http://post.naver.com/viewer/postView.nhn?volumeNo=5542527&memberNo=24659848&vType=VERTICAL
[024_2]: http://tv.naver.com/v/801002
[024_3]: http://masterbuilder.kr/portfolio/우리-내/

[023]: http://www.sie-jungsujin.com/p/portfolio_page/byeol-ddong-jib별똥집/
[023_1]: http://www.smlounge.co.kr/living/article/26295
[023_2]: http://www.vmspace.com/2008_re/kor/sub_emagazine_view.asp?category=architecture&idx=11970&pageNum=1

[022]: http://leenhwang.com/archives/portfolio/판교_yellow-house
[022_1]: http://masterbuilder.kr/portfolio/판교-l주택/
[022_2]: http://blog.naver.com/leehwangarch/220802187352

[021]: http://www.leejaeha.com
[021_1]: http://navercast.naver.com/magazine_contents.nhn?rid=1409&contents_id=20459
[021_2]: http://news.naver.com/main/read.nhn?mode=LSD&mid=sec&sid1=101&oid=366&aid=0000110832

[020]: http://soltos.kr/project/10
[020_1]: http://news.naver.com/main/read.nhn?mode=LSD&mid=sec&sid1=103&oid=020&aid=0002558653
[020_2]: http://www.vmspace.com/2008_re/kor/sub_emagazine_view.asp?category=architecture&idx=11827

[019]: http://www.spacelap.co.kr/new/sub_03_01.html?include=&mode=view&id=1329&lc=1000000&sc=&mc=&gid=photo&
[019_1]: http://www.uujj.co.kr/bbs/board.php?bo_table=house&wr_id=91

[018]: http://www.utaa.co.kr/works.html?year=2016&idx=112
[018_1]: http://navercast.naver.com/magazine_contents.nhn?rid=1433&contents_id=120238

[017]: http://www.johsungwook.com/index.php?/projects/pangyodong-duplex-house/
[017_1]: http://www.jarchiv.com/bbs/board.php?bo_table=portfolio&wr_id=77
[017_2]: http://blog.naver.com/s908028/220441693482
[017_3]: https://www.facebook.com/pages/판교-사이집-思異集/587031538071246

[016]: http://www.koreabluehouse.com/works
[016_1]: http://navercast.naver.com/magazine_contents.nhn?rid=1094&contents_id=127381

[015_1]: http://navercast.naver.com/magazine_contents.nhn?rid=1089&contents_id=117754
[015_2]: http://blog.naver.com/PostThumbnailList.nhn?blogId=rudaruda&from=postList&categoryNo=33

[014]: http://kddh.kr/?page_id=11530
[014_1]: http://www.housingplus.co.kr/home/bbs/board.php?bo_table=p1&wr_id=54&page=2&mNum=2&sNum=0&LNum=
[014_2]: http://navercast.naver.com/magazine_contents.nhn?rid=1433&contents_id=24497

[013]: http://anlstudio.com/db/3091
[013_1]: http://navercast.naver.com/magazine_contents.nhn?rid=1433&contents_id=113993

[012]: http://www.minworkshop.com/index.php?/timber-duplex/
[012_1]: https://www.homify.co.kr/projects/161056/timber-duplex-1-1

[011]: http://ism-architects.com/?fluxus_portfolio=sam-dae-heon
[011_1]: http://navercast.naver.com/magazine_contents.nhn?rid=1094&contents_id=23565

[010]: http://www.a-17.com/a17_test/portfolio_show.php?idx=101&page=1&works_type=PORTFOLIO
[010_1]: https://www.homify.co.kr/projects/89880

[009]: http://jo-jinman.com
[009_1]: http://www.vmspace.com/2008_re/kor/sub_emagazine_view.asp?category=architecture&idx=11975

[008]: http://mlnparchitects.com/?portfolio_page=pangyo-one-roof-house
[008_1]: https://www.ecocellhome.com
[008_2]: https://www.homify.co.kr/ideabooks/245135/아이들의-추억속에-남을-집-판교-One-Roof-House
[008_3]: https://www.youtube.com/watch?v=Se2tmSos3kE
[008_4]: http://navercast.naver.com/magazine_contents.nhn?rid=1433&contents_id=101291

[007]: http://jhyana.com/projects/view.php?prj_no=43
[007_1]: https://www.homify.co.kr/ideabooks/22682/homify-360º-2대가-함께-만들어갈-따뜻한-집,-판교-시전당

[006]: http://www.homento.co.kr/new/04_portfolio/portfolio02.php?board_code=view&sang_no=161
[006_1]: http://navercast.naver.com/magazine_contents.nhn?rid=1433&contents_id=44191

[005]: http://www.trugroup.co.kr/adfontes
[005_1]: http://www.dearchiis.co.kr/bbs/board.php?bo_table=projects&wr_id=78
[005_2]: http://navercast.naver.com/magazine_contents.nhn?rid=1094&rid=&contents_id=57944

[004]: http://www.johsungwook.com/index.php?/projects/pankyodong-543-3w-/
[004_1]: http://navercast.naver.com/magazine_contents.nhn?rid=1433&contents_id=16445

[003]: http://www.guga.co.kr/items/view/work/590
[003_1]: http://news.naver.com/main/read.nhn?mode=LSD&mid=sec&sid1=103&oid=308&aid=0000009739

[002]: http://www.guga.co.kr/items/view/work/945
[002_1]: http://www.stuga.co.kr/
[002_2]: http://navercast.naver.com/magazine_contents.nhn?rid=1433&contents_id=92203

[001]: http://www.o4aa.com/pk
[001_1]: http://navercast.naver.com/magazine_contents.nhn?rid=1433&attrId=&contents_id=130024&leafId=1433
[001_2]: http://news.naver.com/main/read.nhn?mode=LSD&mid=sec&sid1=004&oid=469&aid=0000176335
