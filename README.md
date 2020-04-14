## Installation


**가상환경 설정**

```powershell
C:\Users\Name\Project> python -m venv venv 
C:\Users\Name\Project> myvenv\Scripts\activate
```

```
 '이 스크립트는 이 시스템에서 실행되지 않습니다.'라는 오류 메시지가 표시 될 수 경우 
C:\WINDOWS\system32> Set-ExecutionPolicy -ExecutionPolicy RemoteSigned

The execution policy helps protect you from scripts that you do not trust. Changing the execution policy might expose you to the security risks described in the about_Execution_Policies help topic at http://go.microsoft.com/fwlink/?LinkID=135170. Do you want to change the execution policy? [Y] Yes  [A] Yes to All  [N] No  [L] No to All  [S] Suspend  [?] Help (default is "N"): A
```

**Library 설치**

```powershell
pip install -r requirements.txt
```



**실행**

```
python manage.py runserver
```

----
