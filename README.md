# Mech-Mind Procedure

메크마인드에서 제공하는 Mech-Vision(이하 MV) 프로그램을 사용함에 있어 유용한 기능들을 프로시저로 만들어 공유드립니다.


## 사용방법

필요한, 첨부되어있는 [ .json ] 파일을 다운받은 후 MV에 불러와 사용하면 됩니다.
불러오는 방법은 아래와 같습니다.
1. 프로젝트 생성 또는 적용할 프로젝트 열기
2. 프로젝트의 스텝작업창(그리드)에서 마우스 우클릭
3. [ 파일에서 프로시저 로드 ]를 클릭하여 다운받은 프로시저 불러오기
4. 프로시저 비고에 적힌 파라미터 변동값들을 변경


## 프로시저 목록  

<!-- Convert_Merge Data[변환_데이터 합치기] -->
 - [Cal_Circumcenter of three points](https://github.com/KimJihun-1315/Mech-Mind_Precedure/tree/main/Procedure/Cal_Circumcenter%20of%20three%20points)
 [변환_데이터 합치기]
    <details>
    <summary>Version</summary>
    
    **1.0.0**       
     프로시저 생성

    </details>



<!-- Convert_Merge Data[변환_데이터 합치기] -->
 - [Convert_Merge Data](https://github.com/KimJihun-1315/Mech-Mind_Precedure/tree/main/Procedure/Convert_Merge%20Data)
 [변환_데이터 합치기]
    <details>
    <summary>Version</summary>
    
    **1.0.0**       
     프로시저 생성[압축된 데이터풀고 합치기 3개, 마스크이미지합치기 1개, 포인트클라우드합치기 1개]
     
    **1.0.1**       
    프로시저명 변경 (Convert_merge CompressedData, MaskImage, PointCloud -> Convert_Merge Data), (변환_압축데이터, 마스크이미지, 포인트클라우드 합치기 -> 변환_데이터 합치기기)

    **1.0.2**       
    내부스텝명 수정

    </details>



<!-- Get_Highest PointCloud[취득_최상단 포인트클라우드] -->
 - [Get_Highest PointCloud](https://github.com/KimJihun-1315/Mech-Mind_Precedure/tree/main/Procedure/Get_Highest%20PointCloud)
 [취득_최상단 포인트클라우드]
    <details>
    <summary>Version</summary>
    
    **1.0.0**       
     프로시저 생성
     
    **1.1.0**       
    최상단의 떨어져있는 포인트클라우드 군집이 인식 되지 않는 현상 제거
     
    **1.1.1**       
    프로시저명 변경 (Get_HighestPart PointCloud -> Get_Highest PointCloud), (취득_최상단 포인트클라우드 이미지 -> 취득_최상단 포인트클라우드)

    **1.1.2**       
    내부스텝명 수정

    </details>




<!-- Get_Pose through MaskImage[취득_마스크를 통한 포즈] -->
 - [Get_Pose through MaskImage](https://github.com/KimJihun-1315/Mech-Mind_Precedure/tree/main/Procedure/Get_Pose%20through%20MaskImage)
 [취득_마스크를 통한 포즈]
    <details>
    <summary>Version</summary>
    
    **1.0.0**       
     프로시저 생성[원시포인트클라우드와 마스크를 통하여 포즈획득]

    **1.0.1**       
    내부스텝명 수정

    </details>



<!-- Save_HighestPart(PointCloud) Image[저장_최상단 포인트클라우드 이미지] -->
 - [Save_Highest PointCloud Image](https://github.com/KimJihun-1315/Mech-Mind_Precedure/tree/main/Procedure/Save_Highest%20PointCloud%20Image)
 [저장_최상단 포인트클라우드 이미지]
    <details>
    <summary>Version</summary>

    **1.0.0**       
    프로시저 생성

    **1.1.0**       
    Get_HighestPart PointCloud 1.1.0 패치내용 반영
    프로시저명 변경 (Save_HighestPart Image -> Save_Highest PointCloud Image)

    **1.2.0**       
    Save_Image for PointCloud 1.1.0 패치내용 반영

    **1.2.1**       
    내부스텝명 수정

    </details>


<!-- Save_Image for PointCloud[저장_포인트클라우드에 해당하는 이미지] -->
 - [Save_Image for PointCloud](https://github.com/KimJihun-1315/Mech-Mind_Precedure/tree/main/Procedure/Save_Image%20for%20PointCloud)
[저장_포인트클라우드에 해당하는 이미지]
    <details>
    <summary>Version</summary>
    
    **1.0.0**       
    프로시저 생성

    **1.1.0**
    포인트클라우드 누락으로 생기는 모서리부분의 이미지누락 현상 수정

    **1.1.1**       
    내부스텝명 수정

    </details>


