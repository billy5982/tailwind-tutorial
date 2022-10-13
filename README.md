```html
<!-- 
    package.json 한번에 업데이트하기
    
    npm-check-updates 사용
    
    npm install -g npm-check-updates
    ㄴ 패키지 설치
    
    ncu -u
    ㄴ 업데이트 가능한 항목 확인
    
    npm install 
    ㄴ 업데이트
 -->
<!-- 기본 스타일
    -을 사용하여 사이즈,부가 사항 설정
    []을 이용하면 px단위 및 정확한 색상 지정 가능
    w : 너비
    h : 높이

    // 앞에 -를 붙여서 네거티브 제작 가능
    m : margin  -> ml,mr,mt,mb
    p : padding -> pl,pr,pt,pb
    rounded => 테두리 round -> rounded-tl-[15px] tl,tr,br,bl 가능
    list-disc => ul에 적용, li에 점 생김
    list-decimal => ul에 적용, li에 순서 생김(숫자)
    text : 색상, 크기,위치(center,left 등등) 설정 가능
    space : x,y로 설정 가능 -> 자식요소 간격 설정 space-x-5, space-y-3
    space 는 첫요소를 제외하고 다음요소부터 간격이 들어간다 첫요소는 부모요소에 붙어 있음 flex-wrap 같은 여러줄일 때 문제가 생김
    (flex에선 gap이 유용)
    border : px단위, + 색상 
    inline-block
    leading : line-height
    order : 자식요소에 적용 배치순서 md를 이용해서 no-order도 사용가능
-->

<!-- flex Style
        gap-px   gap : 1px
        gap-x-px  column-gap : 1px;
        gap-1       gap : 0.25rem;
        justify-content: center        - justify-center
        justify-content: space-between - justify-between
        align-items: flex-start        - items-start
        align-items: center            - items-center
        align-self: auto               - self-auto
        align-slef: flex-start         - self-start
        align-slef: flex-end           - self-end
        flex: 1 1 0%                   - flex-1
        flex: 1 1 auto                 - flex-auto
        flex: 0 1 auto                 - flex-initial
        flex: none                     - flex-none
    -->
```
