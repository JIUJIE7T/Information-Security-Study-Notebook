# Business Continuity Plan (Modifying)
BCP stands for Business continuity plan, which is call 事業継続計画 in Japanese, it refers to the plan for business when disaster and other unpredictable event happens.

The BCP usually contains 
- 1st priority business
- Core business RTO
- Emergency Time Service level
- Devices, points replacement plan
- BCP Information sharing


## IT BCP
It BCP is a part of BCP, it means the BCP within IT systems inside a company.   
The purpose of IT BCP is to keep system operate within emergency.  
To protect firms' properties and datas, IT BCP is required.  

### The necessity of integrity with BCP
IT-BCP is necessary for it keeps the complicity of BCP. If there is conflicts between IT-BCP and BCP, there might be influence or impact on BCP and there might be a possibility that the BCP could not be useful when disaster happens.

### Examples
 - Data Backup
 - Replacement or Remote work
 - BCP contact system
 - Internal CSIRT (Computer Security Incident Response Team)
#### BCP invoking flow (Graph being modified)
This graph is refering [第7回 サイバー攻撃に備えたIT-BCPの構築(前編)](https://www.nec-solutioninnovators.co.jp/sl/bcp/series/itbcp.html)




refering to the picture and Japanese rules there are four phases when IT-BCP happens
##### Deserve period
when cyber incident is deserved, depending on the contents there is a possibility to lately catch severe incident.
The Capacity of the sytem might go slight down, or completely keep stable.
##### 1. BCP invoke
when BCP is invoked, the capacity of the system goes dramatically down, or even stops. 
It is hard to determine whether the BCP should be invoked or not.

##### 2. Starting phase
When BCP is completely invoked, replacement of each system will be used. However, this will not be enough for completely prevent the hazard. for the reason of the hazard has not been detected, second time damage is not avoidable.

##### 3. Recovery phase(復旧フェース)
The phase that the system is recoverying and cause/reason of incident is designagted.
Recovery plan is mainly focus on system recovery/restart

##### 4. Returning phase(復帰フェース)
The phase that recovery is finished and prevention of reoccurrence is designed an implemented.
This phase focuses more on prevention for the same incident.

#### CSIRT
 CSIRT is a group/team to invest the causes and to prevent second hazard/damage from incident.

## Means to succeed an IT-BCP

### refer to guideline
Here are several guidelines from Japanese government

- [IT サービス継続ガイドライン｜経済産業省](https://www.meti.go.jp/policy/netsecurity/downloadfiles/itsc_gl.pdf)
- [サイバーセキュリティ経営ガイドライン｜経済産業省](http://warp.da.ndl.go.jp/info:ndljp/pid/10977616/www.meti.go.jp/policy/netsecurity/mng_guide.html)
- [重要インフラにおける情報セキュリティ確保に係る安全基準等策定指針｜サイバーセキュリティ戦略本部](https://www.nisc.go.jp/active/infra/pdf/shishin4.pdf)
- [中央省庁における情報システム運用継続計画ガイドライン｜内閣官房情報セキュリティセンター](https://www.nisc.go.jp/active/general/pdf/itbcp1-1_2.pdf)
- [IT-BCP 策定モデル｜内閣官房情報セキュリティセンター](https://www.nisc.go.jp/active/general/pdf/IT-BCP.pdf)
- [事業継続ガイドライン 第三版｜内閣府](http://www.bousai.go.jp/kyoiku/kigyou/keizoku/pdf/guideline03.pdf)
### Visiblize Business Recovery Plan
  Visiblize and ascertain the following items
  - Person/group in charge of each system
  - Problem and solution for each
  - IT system conponents(Member)
  - Correlation between IT system and business
  - Prediction of recovery from disaster
  
  To be continued
