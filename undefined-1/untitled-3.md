# \[sourcetree\] 외부 비교 프로그램 등록 방법

Visual Diff Tool: Other  
Diff [Command:/usr/local/bin/bcomp](http://command/usr/local/bin/bcomp)  
Parameters:$LOCAL $REMOTE  
Merge Tool: Other  
Merge [Command:/usr/local/bin/bcomp](http://command/usr/local/bin/bcomp)  
Paramters:$LOCAL $REMOTE $BASE $MERGED

---------------------------------------------------------

Beyound Compare 설정 방법:

1. SourceTree에서 Tools-&gt;Options→상단의 Diff 선택
2. External Diff / Merge에서 External Diff Tool: Custom 선택
3. Diff Command: Beyound Compare 경로 선택 \(예시: C:\Program Files \(x86\)\Beyond Compare 2\BC2.exe\)
4. Arguments: $LOCAL $REMOTE
5. OK 클릭.

이후 External Diff를 누르면 Beyound Compare가 켜진다.

