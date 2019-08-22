# boostCourse
부스트코스 미션별 학습내용


PJT 2 - 회원 가입 화면 구성 학습내용
- UIDatePicker - pickerMode 설정 가능 ( ex) time , date 등 ) 
               - valueChanged로 사용하여 DateFormatter로 변환하여 데이터 가져오는 컴포넌트
- viewDidLoad 와 viewWillLayoutSubviews 의 성능 차이점 공부

PJT 3 - 기상정보 어플리케이션
- Codable = Codable 사용 시 codingkey를 사용하면 json의 스네이크 케이스와 원하는 변수에 대해서 매핑 가능

PJT 4 - 사진관리 어플리케이션
- PHPhotoLibrary.shared().register(self) - 갤러리의 변화르 감지하여 데이터를 최신화 가능 ( 삭제 , 즐겨찾기 등)
- navigationBar.prefersLargeTitles - 기존의 네비게이션보다 큰 타이틀 사용 가능 스크롤 시 자동으로 이전 기본 모델로 유연 동작
- OperationQueue - 연산 횟수를 제한 할 수 있고 연산에 특화 된 DispatchQueue와는 다른 큐 

PJT 5 - 영화정보 어플리케이션
- contentVerticalAlignment - TextField의 텍스트 상하 위치르 지정할 수 있는 프로퍼티
- Notificataion UserInfo - userinfo를 통해서 데이터 전달 받아서 활요 가능
