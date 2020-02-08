# SearchController
We'll learn how to treat SearchController, and UITableViewController
몇가지 작업이 필요했다.
먼저 첫번째 뷰 컨트롤을 'Embed in'의 네비게이션 탭으로 둘러싸보자.
1. 그 첫 번째 뷰에 테이블뷰를 넣고, ViewController에 Outlet변수로 연결시킨다.
2. 테이블뷰에 넣을 셀에 대한 파일과, Xib파일을 각각 만든다. 그리고 이 코드를 tableView.register함수를 통해서 셀을 테이블 뷰에 '연결'시킨다.
 -->  테이블 뷰에 셀을 연결시킨것이 완료
3. 그 다음 테이블 뷰의 네비게이션 텝에 SearchController를 연결해준다.
4. searchController.searchresultUpdater을 통해, SearchBar에 문자열을 적을 때마다 계속 업데이트함으로써 업데이트해준다.
5. 이번에는 단순 하나의 ViewController.swift로 완성한 것이 아닌, CellTableView의 파일과, 그것의 Xib파일을 만들어줌으로써, 첫번째 뷰에 연결해주었다. 어떻게 보면 심플하지만, 꽤나 복잡한 과정이기에 반복적 학습이 필요한 것으로 보인다.

------------------------------------------------------------------------
혹시 이 코드보다 간단한게 있다면 커밋해주시면 공부하는데 큰 도움이 될 것 같습니다. 
감사합니다. 
