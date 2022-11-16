# Secure Smart Contract library (SSC)

```mermaid
gantt
    dateFormat  YYYY-MM-DD
    title       Secure Smart Contract (SSC)
    excludes    weekends

    section Swap Contract Template (BR04,BR05)
    Protocol design                     :protocol1, 2022-11-22,30h
    Smart contract development          :dev1, after protocol1, 90h
    Javascript SDK                      :sdk1, after dev1, 50h
    User documentation                  :after sdk1, 40h
    Technical documentation             :docs1, after sdk1, 25h
    Ricardian Contracts                 :after sdk1, 15h
    Unit Testing                        :testing1, after docs1, 70h
    User Testing                        :after docs1, 50h
    Audit                               :audit1, after testing1, 40h

    section Flash Loan Template (BR08,BR09)
    Protocol design                     :protocol2, after audit1, 10h
    Smart contract development          :dev2, after protocol2, 65h
    Javascript SDK                      :sdk2, after dev2, 35h
    User documentation                  :after sdk2, 30h
    Technical documentation             :docs2, after sdk2, 16h
    Ricardian Contracts                 :after sdk2, 10h
    Unit Testing                        :testing2, after docs2, 55h
    User Testing                        :after docs2, 50h
    Audit                               :audit2, after testing2, 40h

    section Stable Coin Contract Template (BR10,BR11,BR12)
    Protocol design                     :protocol3, after audit2, 70h
    Smart contract development          :dev3, after protocol3, 117h
    Javascript SDK                      :sdk3, after dev3, 65h
    User documentation                  :after sdk3, 25h
    Technical documentation             :docs3, after sdk3, 25h
    Ricardian Contracts                 :after sdk3, 15h
    Unit Testing                        :testing3, after docs3, 90h
    User Testing                        :after docs3, 70h
    Audit                               :audit3, after testing3, 40h

    section Lending Contract Template (BR13,BR14,BR15,BR16)
    Protocol design                     :protocol4, after audit3, 80h
    Smart contract development          :dev4, after protocol4, 127h
    Javascript SDK                      :sdk4, after dev4, 65h
    User documentation                  :after sdk4, 25h
    Technical documentation             :docs4, after sdk4, 25h
    Ricardian Contracts                 :after sdk4, 15h
    Unit Testing                        :testing4, after docs4, 100h
    User Testing                        :after docs4, 70h
    Audit                               :audit4, after testing4, 40h

    section NFT Standard Template (BR06,BR07)
    Smart contract development          :dev5, after audit4, 45h
    User documentation                  :after dev5, 15h
    Technical documentation             :docs5, after dev5, 11h
    Unit Testing                        :testing5, after docs5, 17h
    User Testing                        :after docs5, 20h

    section Audit phases

    section Development Kit (BR01,BR02,BR03)
    Library manager                     :2022-11-22,130h
    Starter kit                         :50h
    Log Utility Contract                :70h

    section Price Feed (BR17, BR18)
    Price Feed Utility Contract         :70h
    Price Feed Trigger                  :50h
    Ricardian Contracts                 :15h
    User documentation                  :40h
    Technical documentation             :50h
    Unit Testing                        :65h
    User Testing                        :65h
```
