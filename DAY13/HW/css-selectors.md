### CSS 선택자

수업 중 정리 예정...

유형 | 선택자 | 설명
--- | --- | ---
**일반 선택자** | E | 요소 선택자
 | E(P) E(C) | 자손 선택자
**속성 선택자** | [attr^="value"] | 시작하는 속성 값이 일치하는 경우 선택
        | [attr$="value"] | 끝나는 속성 값이 일치하는 경우 선택
        | [attr*="value"] | 속성 값을 포함하는 경우 선택
        | [attr|="value"] | 하이픈(-)으로 구분되는 단어가 일치할 때 선택
        | [attr~="value"] | 공백으로 구분되는 단어가 일치할 때 선택
        | [attr operator value i] | 대소문자 상관 없이 해당 value와 같은 것을 선택
**가상 클래스** | :link | <a> 요소의 기본 상태
        | :visited | <a> 요소의 방문한 상태
        | :hover | 요소에 마우스 커서가 올라간 상태
        | :active | 요소를 마우스 커서로 누른 상태
        | :focus | 요소에 키보드 포커스가 적용된 상태
        | :nth-child(an + b) | 부모 요소의 자식 요소 중, 수학 표현식에 따른 계산 결과를 처리 후 선택
        | :first-child | 부모 요소의 첫번째 자식 요소일 경우 선택
        | :last-child | 부모 요소의 마지막 자식 요소일 경우 선택
        | :only-child | 부모 요소의 유일한 자식 요소일 경우 선택
        | :not(selector) | () 안의 선택자를 제외한 나머지 대상 요소 선택
        | :nth-last-child(an + b) | 부모 요소의 자식 요소 중, 수학 표현식에 따른 계산 결과를 처리 후 선택 (뒤로부터 색인)
        | :nth-of-type(an + b) | 동일한 유형 중, 수학 표현식에 따른 계산 결과를 처리 후 선택
        | :nth-last-of-type(an + b) | 동일한 유형 중, 수학 표현식에 따른 계산 결과를 처리 후 선택 (뒤로부터 색인)
**가상 요소** | :root | 루트 요소 선택
        | :empty | 요소 내 내용이 빈 경우 선택
        | :target | 문서의 URI의 조각 식별자(/#id)를 가진 요소 선택
        | :enabled | 폼 요소 컨트롤 중 활성화
        | :disabled | 폼 요소 컨트롤 중 비활성화
        | :checked | (라디오 버튼 혹은 체크박스)폼 요소 중 체크된 것
        | :invalid |
        | :read-only |
        | :read-write |
        | :optional |
        | :out-of-range |
        | :lang(language) | 요소에 lang 속성이 language인 것을 선택(속성 선택자가 더 직관적일 수 있다)
