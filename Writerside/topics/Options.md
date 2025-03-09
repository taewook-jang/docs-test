# Options

### animModel

<shortcut>Type</shortcut> object   <shortcut>Default</shortcut> { on: undefined, duration: 290 }

그리드에서 정렬, 필터링, 행 확장, 열 크기 조정, 재정렬 등을 수행하는 동안 셀 전환의 애니메이션을 구성합니다. (v5.5.0)

on:  애니메이션을 활성화/비활성화합니다.

duration: 애니메이션의 지속 시간을 밀리초 단위로 제어합니다.

**Code examples:**
지정된 animModel 옵션으로 pqGrid를 초기화합니다.

<code-block lang="javascript">
//turn animations on and set a new duration.
pq.grid( selector, {
    animModel:  { on: true, duration: 400 }
});
</code-block>

### autoAddCol

<shortcut>Type</shortcut> object   <shortcut>Default</shortcut> undefined

(v8.3.0) 그리드의 가장 오른쪽에 보이는 열에서 오른쪽 키를 누르면 빈 열이 자동으로 추가됩니다.

**Code examples:**
자동 추가 콜 옵션을 지정하여 pqGrid를 초기화합니다.

<code-block lang="javascript">
pq.grid( selector, {
    animModel:  { autoAddCol: true }
});
</code-block>

### autoAddRow

<shortcut>Type</shortcut> object   <shortcut>Default</shortcut> undefined

(v8.3.0) 그리드의 마지막 보이는 행에서 아래쪽 키를 누르면 빈 행이 자동으로 추가됩니다.

**Code examples:**
자동 추가 콜 옵션을 지정하여 pqGrid를 초기화합니다.

<code-block lang="javascript">
pq.grid( selector, {
    animModel:  { autoAddRow: true }
});
</code-block>

### autofill

<shortcut>Type</shortcut> Boolean   <shortcut>Default</shortcut> true

이 옵션은 채우기 핸들 옵션과 함께 작동합니다. 이 옵션이 참이면 그리드는 채우기 핸들을 셀에 드래그할 때 숫자 및 날짜 데이터 유형의 패턴 또는 계열을 파악합니다.

**Code examples:**
자동 채우기 옵션을 지정하여 pqGrid를 초기화합니다.

<code-block lang="javascript">
//turn autofill off.
pq.grid( selector, { autofill: false } );
</code-block>

