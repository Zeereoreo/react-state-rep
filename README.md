## fe-sprint-statesairline-client
async를 useEffect에서 사용할 떄 useEffect 첫 번쨰 함수에서 사용 할 경우 에러가 난다.
async는 프로미스 객체를 리턴하기 때문에
첫 번째 함수에서 사용하는게 아닌, (async()=>{} )() (가장 최신 방법)를 쓴다.
