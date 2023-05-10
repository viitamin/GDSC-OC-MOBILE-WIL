# 덕부름 UI 따라만들기

/*
import 'package:flutter/material.dart';
import 'package:week5/common/const/colors.dart';
import 'package:week5/common/const/text.dart';
import 'package:week5/components/duck_logo.dart';

class HomePage extends StatelessWidget {
  const HomePage({super.key});

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        backgroundColor: WHITE,
        title: const DuckLogo(),
        centerTitle: false,
        elevation: 0.0,
      ),
      body: ListView(
        children: [
          Container(
            margin: const EdgeInsets.symmetric(
              horizontal: 20.0,
              vertical: 8.0,
            ),
            padding: const EdgeInsets.symmetric(
              horizontal: 14.0,
              vertical: 10.0,
            ),
            decoration: BoxDecoration(
              color: GREY100,
              borderRadius: BorderRadius.circular(8.0),
            ),
            child: Row(
              children: const [
                Text(
                  "공지",
                  style: TextStyle(
                    fontSize: 13,
                    fontWeight: W800,
                    color: GREY900,
                    letterSpacing: -0.25,
                  ),
                ),
                SizedBox(width: 10),
                Text(
                  "덕부름에 새로운 기능이 추가됐어요.",
                  style: TextStyle(
                    fontSize: 13,
                    fontWeight: W500,
                    color: GREY900,
                    letterSpacing: -0.25,
                  ),
                ),
              ],
            ),
          ),
          const SizedBox(
            height: 15,
          ),
          Container(
            margin: const EdgeInsets.fromLTRB(20, 0, 20, 0),
            decoration: BoxDecoration(
              borderRadius: BorderRadius.circular(12),
            ),
            child: ClipRRect(
              borderRadius: BorderRadius.circular(12),
              child: Image.asset(
                './assets/images/le.png',
                width: 335,
                height: 192,
                fit: BoxFit.cover,
              ),
            ),
          ),
          const SizedBox(
            height: 30,
          ),
          Container(
            width: 100,
            height: 80,
            margin: const EdgeInsets.fromLTRB(20, 0, 20, 0),
            padding: const EdgeInsets.only(left: 18, right: 20),
            decoration: BoxDecoration(
              color: Colors.black,
              borderRadius: BorderRadius.circular(12),
            ),
            child: Row(
                mainAxisAlignment: MainAxisAlignment.spaceBetween,
                children: [
                  Column(
                    mainAxisAlignment: MainAxisAlignment.center,
                    crossAxisAlignment: CrossAxisAlignment.start,
                    children: const [
                      Text('심부름 신청하러 가기',
                          style: TextStyle(
                            color: Colors.white,
                            fontSize: 16,
                          )),
                      Text('덕질 관련 심부름을 시청해 보세요!',
                          style: TextStyle(
                            color: Colors.grey,
                            fontSize: 14,
                          )),
                    ],
                  ),
                  const Icon(
                    Icons.arrow_circle_right,
                    color: Colors.grey,
                    size: 40,
                  )
                ]),
          ),
          const SizedBox(height: 15),
          Container(
            width: 100,
            height: 80,
            margin: const EdgeInsets.fromLTRB(20, 0, 20, 0),
            padding: const EdgeInsets.only(left: 18, right: 20),
            decoration: BoxDecoration(
              color: Colors.green[50],
              borderRadius: BorderRadius.circular(12),
            ),
            child: Row(children: [
              Container(
                width: 48,
                height: 48,
                margin: const EdgeInsets.only(right: 17),
                alignment: Alignment.center,
                decoration: BoxDecoration(
                    color: Colors.green[200],
                    borderRadius: BorderRadius.circular(100)),
                child: const Text('Tip!'),
              ),
              Column(
                crossAxisAlignment: CrossAxisAlignment.start,
                mainAxisAlignment: MainAxisAlignment.center,
                children: [
                  const Text(
                    '덕부름 이용방법',
                    style: TextStyle(fontSize: 17, fontWeight: FontWeight.bold),
                  ),
                  Row(
                    children: const [
                      Text(
                        '덕부름의 이용 방법을 알아보세요!  ',
                        style: TextStyle(
                          fontSize: 13,
                        ),
                      ),
                      Icon(
                        Icons.arrow_forward_ios,
                        size: 15,
                      ),
                    ],
                  )
                ],
              )
            ]),
          ),
          const SizedBox(
            height: 35,
          ),
          Container(
            margin: const EdgeInsets.fromLTRB(24, 0, 24, 0),
            child: Row(
                mainAxisAlignment: MainAxisAlignment.spaceBetween,
                children: const [
                  Text(
                    '최근 등록된 심부름',
                    style: TextStyle(fontSize: 18),
                  ),
                  Text('더보기 >', style: TextStyle(fontSize: 13, color: GREY500)),
                ]),
          ),
          const SizedBox(
            height: 14,
          ),
          Container(
            decoration: BoxDecoration(
                border: Border.all(color: GREY500),
                borderRadius: BorderRadius.circular(14)),
            child:
                Column(crossAxisAlignment: CrossAxisAlignment.start, children: [
              Container(
                child: const Text('시급 1만원'),
              ),
              const Text('서울 광진구'),
              Row(
                children: [
                  Container(
                    child: const Text('팬싸 대리응모'),
                  ),
                  Container(
                    child: const Text('+2'),
                  ),
                ],
              ),
              const Text('8/6 오후 8:00')
            ]),
          ),
        ],
      ),
    );
  }
}
*/
### 현재 미완성, 진행중입니다
