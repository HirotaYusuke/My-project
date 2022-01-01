# Medical Appointment No Shows（医療機関予約者の来診予測）

---

## 課題設定

医療機関の予約を行った患者は，予約日について事前に案内を受け取っているにもかかわらず，予約日に突然キャンセルし，来診しないことがある．

このことにより，医療機関側がスケジュール通りに診察を行うことができず，無駄な時間が生まれてしまうだけでなく，利益損失，医療従事者のモチベーション低下につながる．また，患者側にとっても，診察が予定よりも遅れることにより，治療箇所発見の遅れや治療の遅れにつながることが考えられる．

このような課題を解決するため，医療機関は予約制度・予約システムの見直し，改善をすることにした．キャンセル防止のため，「キャンセル待ち」機能を備えた予約システムを導入する．そこで，医療機関はキャンセル防止のための，どのような患者が当日に予約を急遽キャンセルする傾向にあるのかを分析することとなった．

---
## データセット
本分析は，Kaggleによって公開されている「[Medical Appointment No Shows](https://www.kaggle.com/joniarroba/noshowappointments)」というデータセットを使用する．

### データの概要
110.527件の診療予約についてそれぞれ14変数がある．最も重要である変数は，患者が来診したか否か，という変数である．
14変数 [PatientId, AppointmentID, Gender
, DataMarcacaoConsulta, DataAgendamento, Age, Neighbourhood, Scholarship, Hipertension, Diabetes, Alcoholism, Handcap, SMS_received, No-show]

#### データについて
- 1  PatientId(患者ID)
  - Identification of a patient
- 2　AppointmentID(予約ID)
  - Identification of each appointment
- 3　Gender(性別)
  - Male or Female . Female is the greater proportion, woman takes way more care of they health in comparison to man.
- 4　DataMarcacaoConsulta(予約日)
  - The day of the actuall appointment, when they have to visit the doctor.
- 5　DataAgendamento(予約した日から予約日までの日数)
  - The day someone called or registered the appointment, this is before appointment of course.
- 6　Age(年齢)
  - How old is the patient.
- 7　Neighbourhood(医療機関)
  - Where the appointment takes place.
- 8 Scholarship(医療補助金を受け取っていたか否か)
  - True of False
- 9 Hipertension
  - True or False(高血圧か否か)
- 10 Diabetes(糖尿病か否か)
  - True or False
- 11 Alcoholism(アルコール依存症か否か)
  - True or False
- 12 Handcap(障がいを持っているか否か)
  - True or False
- 13 SMS_received(SMSを受け取ったか否か)
  - 1 or more messages sent to the patient.
- 14 No-show(来診したか否か)
  - True or False.

8 Scholarship(奨学金)についての詳細は，[Wikipedia](https://en.wikipedia.org/wiki/Bolsa_Fam%C3%ADlia)を参照

目的変数：No-show 
---


