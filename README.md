TwitterBootStrap3-DataTables
============================

DataTablesをTwitterBootStrap3のUIにmergeしたもの

##使い方

* CSSとJSを読み込む
* dataTables.min.jsのあとにDT_bootstrap.jsを読み込むこと
* tableをhtmlで作成する
* jsで呼び出す

##例
``` 
<head>

  <link rel="stylesheet" type="text/css" href="../css/DT_bootstrap.css">
  <!-- jQuery -->
  <script type="text/javascript" charset="utf8" src="http://ajax.aspnetcdn.com/ajax/jQuery/jquery-1.8.2.min.js"></script>
  <!-- DataTables -->
  <script type="text/javascript" charset="utf8" src="http://ajax.aspnetcdn.com/ajax/jquery.dataTables/1.9.4/jquery.dataTables.min.js"></script>
  <!-- DT_bootstrap -->
    <script type="text/javascript" charset="utf8" src="../js/DT_bootstrap.js"></script>
</head>


<table id="table_id">
    <thead>
        <tr><th>Column 1</th><th>Column 2</th><th>etc</th></tr>
    </thead>
    <tbody>
    	<tr><td>Row 0 Data 1</td><td>Row 0 Data 2</td><td>etc</td></tr>
        <tr><td>Row 1 Data 1</td><td>Row 1 Data 2</td><td>etc</td></tr>
        <tr><td>Row 2 Data 1</td><td>Row 2 Data 2</td><td>etc</td></tr>
        <tr><td>Row 3 Data 1</td><td>Row 3 Data 2</td><td>etc</td></tr>
        <tr><td>Row 4 Data 1</td><td>Row 4 Data 2</td><td>etc</td></tr>
        <tr><td>Row 5 Data 1</td><td>Row 5 Data 2</td><td>etc</td></tr>
        <tr><td>Row 6 Data 1</td><td>Row 6 Data 2</td><td>etc</td></tr>
        <tr><td>Row 7 Data 1</td><td>Row 7 Data 2</td><td>etc</td></tr>
        <tr><td>Row 8 Data 1</td><td>Row 8 Data 2</td><td>etc</td></tr>
        <tr><td>Row 9 Data 1</td><td>Row 9 Data 2</td><td>etc</td></tr>
        <tr><td>Row A Data 1</td><td>Row A Data 2</td><td>etc</td></tr>
        <tr><td>Row B Data 1</td><td>Row B Data 2</td><td>etc</td></tr>
    </tbody>
</table>


<script>
$(document).ready(function(){
  $('#table_id').dataTable();
});
</script>
```

基本的な使い方は公式サイトを参考にしてください  
<http://datatables.net/>
