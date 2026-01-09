## Q&A Sheet Link

https://docs.google.com/spreadsheets/d/1mUKD6ViId2d-Qv4WHPwvE4lapMUNu6ssxM8klwSSduY/edit?usp=sharing

## remove Replication

    mc replicate ls myminio/mybucket
    
    mc replicate rm --all --force myminio/mybucket --id rule123

## Resource Quota Commands

    mc quota set local/test --size 1GiB
    
    Output: Successfully set bucket quota of 1.0 TiB on `test


    mc quota info local/test
    
    Output: Bucket `test` has hard quota of 1.0 iB

## FINAL QUIZ

https://forms.office.com/r/ws4v5jfjt0

## FINAL FEEDBACk

https://forms.gle/EPRMrxtJznKYaPjM9


