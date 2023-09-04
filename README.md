# webHTML
웹만들기
<!DOCTYPE html>
<html>
    <head><title>텍스트 입력 폼</title></head>
<body>
<h3>자기 소개서 작성</h3>
<hr>
<form>
    이름 : <input type="text" value=""><br>
    암호 : <input type="password" value="" maxlength="4"><br>
    자소서 : <textarea cols="20" rows="5">
    저는 엘비스입니다. 저를 채용해주시면 최고의 회사를 만들겠습니다.
        </textarea>
        <br>

나라 : <input type="text" list="countries"><br>
			<datalist id="countries">
				<option value="가나">
				<option value="스위스">
				<option value="브라질">
			</datalist>
보고싶은것 : <input type="text" list="what"><br>
			<datalist id="what">
				<option value="산">
				<option value="바다">
				<option value="도시">
			</datalist>
</form>
</body>
</html>
