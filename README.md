# leetcode

![화면 캡처 2024-06-21 161950](https://github.com/Yoo-Jaehyuk/leetcode/assets/63570503/8bd3f44a-263d-4a2c-8dc3-60767444f6de)







음주운전과 관련해서 사회적 시선이 많이 바뀌었다고 느꼈습니다.
과거에는 음주운전에 대해 사회생활을 하다보면 충분히 일어날 수 있는 실수로 보았던 것에 반해
최근에는 음주운전은 살인미수에 준하는 행동이라는 말까지 나오는 만큼 사회적 시선이 급변하였습니다.
저는 이러한 시선의 변화를 보며 음주운전이 다른 범죄들과 다른 양상을 띠고 있다는 생각이 들었습니다.

음주운전은 그 행동만으로 끔찍한 결과가 초래될 것이라고 상상하기 어려운 점에서 그러합니다.
음주운전으로 인한 결과가 상상되기 어려운 만큼 사람들은 음주운전을 하는 것에 대한 죄책감이나 거부감이 적게 들 것이라 생각했고,
이것은 과거의 음주운전에 대한 인식과 크게 연관되어 있다고 생각했습니다.
이러한 음주운전의 특수성은 음주운전의 결과에 대한 책임회피로 이어지게 됩니다.
저번에 했을 때는 아무일도 없었더라든가 다른 사람이 했을 때는 괜찮았다든가 하는 생각을 하면서 말입니다.

그래서 저는 음주운전과 다른 범죄들 간의 관계에 대해 관심을 가져보았습니다.
그래서 음주운전과 절도, 폭행, 사기 이 3개의 다른 범죄들 간의 상관관계와 회귀분석을 하였습니다.
절도, 폭행, 사기는 서로 다른 범죄로 분류가 됩니다.
절도는 절도범죄, 폭행은 폭행범죄, 사기는 지능범죄입니다.

저의 가설은 음주운전과 사기의 상관관계가 가장 높고 기울기 또한 가장 클 것이라는 것이었습니다.
앞의 두 범죄와 달리 사기는 사기로 인한 결과가 그 사람에게 직접적으로 안 느껴지기 때문이었습니다.
물론 차이가 없는 것은 아닙니다.
사기에 대한 결과가 자신에게 긍정적인 결과로 돌아오며 그 결과가 절도나 폭행에 비해서 덜 할 뿐 충분히 시각화, 현실화 된다는 점이 그렇습니다.
이점은 이 프로젝트에 있어서 보완해야할 부분이기도 합니다.
하지만 다른 두 범죄에 비해서는 책임회피적 관점에서 음주운전과 확실히 더 유사하다고 생각했습니다.

그래서 도로교통공단에서 '부문별_음주운전_교통사고 자료', 경찰청에서 '범죄_발생_지역별_통계'. 그리고 마지막으로 '시군별_세대_및_인구' 자료를 찾았습니다.
각 지역 중 경기도의 시에 대해서 자료를 정리해서 프로젝트를 진행했습니다.

마지막으로 보완하고 싶은 부분을 말씀드리겠습니다.
사기와 음주운전이 책임회피적 측면에서 비슷하다고 생각을 했고
이는 지역에 따라 비슷한 양상을 보인다 보다는 정확히 말하면 문화 그룹에 따른 차이가 있을 것이라고 생각을 했었습니다.
그 중에서 교육이 가장 큰 영향을 미칠 것이라 생각했는데 다만 이 교육이 학업적 교육과는 차이가 있는 만큼
이를 대표할 수 있는 자료를 찾는 것에 애를 많이 먹었고 실제로도 지역으로만 나눌 수밖에 없었습니다.
이 부분이 가장 아쉽습니다.
또한 앞서 말씀드렸다 싶이 사기와 음주운전은 분명 차이가 큽니다.
저는 이런 점에서는 오히려 도박이 더 비슷할 수 있다고 생각을 했는데
도박 범죄 데이터를 보면 중간중간에 크게 튀는 부분들이 있어서 쓰기 힘들었습니다.
예를 들어 저는 이번에 경기도를 지역별로 나눠서 프로젝트를 진행했는데
수원 같은 경우 다른 도시들이 50 이하에서 나올 때 혼자 647번의 도박이 적발되어 데이터로서 의미가 없을 것이라고 생각했습니다.


