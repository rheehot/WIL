* `useState()` : 상태를 정의하고 해당 상태를 업데이트하는 함수를 정의할 때 사용한다.
* `useEffect()` : 생명주기를 제어하기 위해 사용한다. (일괄처리)
* `useRef()` : 변하는 값을 저장하기 위해 사용, 이 값이 업데이트 되도 렌더링 발생 안함
* `useMemo()` : 메모이제이션을 하여 값비싼 계산의 결과값을 저장하는 용도, 보통 함수의 리턴 값 유지
* `useCallback()` : 함수 자체를 저장하여 사용하기 위한 것.

Hooks를 사용하면 그 안의 코드가 렌더링 될 때마다 실행되기 때문에 여러가지 비효율적인 부분이 있을 수 있다. 따라서 위와 같은 API들을 활용하여 비효율성을 개선할 수 있다.