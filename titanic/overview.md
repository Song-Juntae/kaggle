도전 과제

    타이타닉호의 침몰은 역사상 가장 악명 높은 난파선 중 하나입니다.

    1912년 4월 15일, 처녀 항해 중 "침몰할 수 없는" RMS 타이타닉호가 빙산과 충돌하여 침몰했습니다. 불행히도 탑승한 모든 사람을 위한 구명정이 충분하지 않아 승객과 승무원 2224명 중 1502명이 사망했습니다.

    생존에는 운의 요소가 어느 정도 개입되어 있었지만, 일부 집단의 사람들은 다른 집단보다 생존할 가능성이 더 높았던 것으로 보인다.

    이 챌린지에서는 승객 데이터(예: 이름, 나이, 성별, 사회 경제적 계층 등)를 사용하여 "어떤 종류의 사람들이 생존할 가능성이 더 높습니까?"라는 질문에 답하는 예측 모델을 구축하도록 요청합니다.

이 대회에서는 어떤 데이터를 사용하나요?

    이 대회에서는 이름, 나이, 성별, 사회 경제적 계층 등과 같은 승객 정보를 포함하는 두 개의 유사한 데이터 세트에 액세스할 수 있습니다. 한 데이터 세트의 제목은 이고 다른 데이터 세트의 제목은 입니다.train.csvtest.csv

    Train.csv 탑승한 승객의 하위 집합(정확히는 891명)에 대한 세부 정보가 포함되며 중요한 것은 "지상 진실"이라고도 하는 생존 여부를 밝힐 것입니다.

    데이터 세트에는 유사한 정보가 포함되어 있지만 각 승객에 대한 "실측 자료"는 공개되지 않습니다. 이러한 결과를 예측하는 것이 여러분의 임무입니다.test.csv

    데이터에서 찾은 패턴을 사용하여 탑승한 다른 418명의 승객(에서 발견)이 생존했는지 여부를 예측합니다.train.csvtest.csv

    "데이터" 탭을 확인하여 데이터 세트를 더 자세히 살펴보세요. 경쟁력 있는 모델을 만들었다고 생각되면 Kaggle에 제출하여 순위표에서 다른 Kaggler와 비교하여 모델이 어디에 있는지 확인하세요.

Data Dictionary
Variable	Definition	Key
survival	Survival	0 = No, 1 = Yes
pclass	Ticket class	1 = 1st, 2 = 2nd, 3 = 3rd
sex	Sex	
Age	Age in years	
sibsp	# of siblings / spouses aboard the Titanic	
parch	# of parents / children aboard the Titanic	
ticket	Ticket number	
fare	Passenger fare	
cabin	Cabin number	
embarked	Port of Embarkation	C = Cherbourg, Q = Queenstown, S = Southampton