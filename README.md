<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HIDC Card</title>
    <style>
        . body {
            font-family: Arial, sans-serif;
            background-color: #2167ac;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100px;
            margin: 0;
        }

        .card {
            width: 500px;
            height: 500px;
            position: relative;
            background-image: url("commentInput.png");
            background-size: cover;
            background-position: center;

        }

        .header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 20px;
        }

        .header div {
            text-align: center;
        }

        .header h2 {
            margin: 5px 0;
            font-size: 24px;
        }

        /* 공통 스타일 */
.position_relative {
    position: relative;
    left: 20px;
}

.display_inline_block {
    display: inline-block;
}

.left {
    text-align: left;
    text-align: 10px;
}

/* 특정 요소에 스타일 적용 */
#tbl_to {
    /* 원하는 스타일을 추가할 수 있습니다 */
    width: 50%; /* 필요에 따라 변경 가능 */
    padding: 5px;
    margin-top: 100px;
    border: 1px solid #cccccc00;
}

#tbl_to::placeholder {
    color: #888; /* 예시: 플레이스홀더 색상 */
}

/* 공통 스타일 */
.position_relative {
    position: relative;
}

.display_inline_block {
    display: inline-block;
}

.left {
    text-align: left;
}

.Pretendard {
    font-family: 'Pretendard', sans-serif;
}

/* 특정 요소에 스타일 적용 */
#tbl_desc {
    width: 100%;
    height: 100px;
    padding: 10px;
    border-radius: 5px;
    border: 1px solid #cccccc00;
    box-sizing: border-box;
}

#tbl_desc::placeholder {
    color: #aaa; /* 예시: 플레이스홀더 색상 */
    font-size: 14px;
}

/* 공통 스타일 */
.position_relative {
    position: relative;
    left: 5px;
}

.display_inline_block {
    display: inline-block;
}

.left {
    text-align: left;
}

.Pretendard {
    font-family: 'Pretendard', sans-serif;
}

/* 특정 요소에 스타일 적용 */
#tbl_from {
    /* 원하는 스타일을 추가할 수 있습니다 */
    width: 50%; /* 필요에 따라 변경 가능 */
    padding: 5px;
    margin-top: 80px;
    border: 1px solid #cccccc00;
}

#tbl_from::placeholder {
    color: #888; /* 예시: 플레이스홀더 색상 */
}

/* 공통 스타일 */
.position_relative {
    position: relative;
}

.display_inline_block {
    display: inline-block;
}

.center {
    text-align: center;
}

/* 버튼 스타일 */
button {
    width: 100%;
    padding: 10px 20px;
    background-color: #9db1d6; /* 버튼 배경색 (필요에 따라 변경 가능) */
    color: white; /* 버튼 텍스트 색상 */
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: 14px;
    font-weight: bold;
    box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
    transition: background-color 0.3s;
}

button:hover {
    background-color: #2d55f6; /* 호버 시 배경색 */
}

.submit {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 150px; /* 필요에 따라 조정 */
}
    
    </style>
</head>
</body>
    <div class="card">
        <div class="header">
            <div class="arrival"></div>
            <div class="to"></div>
            <div class="desc"></div>
            <div class="from"></div>
        </div>

        <div class="to">
            <label class="position_relative display_inline_block left " for="tbl_to">TO.</label>
            <input type="text" class="position_relative display_inline_block left " id="tbl_to" name="tbl_to" placeholder="받는사람">
            </div>

            <div class="desc">
                <textarea id="tbl_desc" name="tbl_desc" cols="30" rows="10" class="position_relative display_inline_block left Pretendard" placeholder="4년동안 수고한 문화콘텐츠테크놀러지 학생들에게 응원의 메세지를 적어주세요."></textarea>
            </div>

            <div class="from">
                <div class="position_relative display_inline_block left">
                    <label class="position_relative display_inline_block left " for="tbl_from">From.</label>
                    <input type="text" class="position_relative display_inline_block left " id="tbl_from" name="tbl_from" placeholder="보내는사람">
                </div>
        </div>
        
        <div class="submit">
            <button type="button" onclick="frmWrite.submit();" class="position_relative display_inline_block center">메세지 전송</button>
        </div>
    </div>
</body>
</html>
