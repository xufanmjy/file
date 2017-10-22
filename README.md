		`						Api文档
		//登录
		/*
		$url = "http://127.0.0.1/api/api.php?c=admin&m=login";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
        $post_data = array (
          "auth" => $auth,
          "name" => "admin",
          "pwd" => "123456",
		  "authTime"=>time()
        );
		*/
		//添加admin
		/*
		$url = "http://127.0.0.1/api/api.php?c=admin&m=add";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
          "uname" => "admin",
          "pwd" => "123456",
		  "authTime"=>time()
        );
		*/
		//查看admin
		/*
		$url = "http://127.0.0.1/api/api.php?c=admin&m=getUser";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "id"=>'18', //可填
		  "page"=>1,
		  "authTime"=>time()
        );
		*/
		//修改admin
		/*
		$url = "http://127.0.0.1/api/api.php?c=admin&m=update";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "authTime"=>time(),
		  "id"=>18,
		  "fid"=>'1', //可填
		  "mobile"=>'321',  //可填
		  "pwd"=>'123456',  //可填
		  "uname"=>'aaa',   //可填
		  "image"=>'image', //可填	  
		  "status"=>'1' //0  可用 1 禁用  2异常
        );
		*/
		//删除admin
		/*
		$url = "http://127.0.0.1/api/api.php?c=admin&m=delete";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "authTime"=>time(),
		  "id"=>18,
        );
		*/
		//收索用户账号
		/*
		$url = "http://127.0.0.1/api/api.php?c=user&m=search";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "authTime"=>time(),
		  "page"=>'1',
		  "isSaler"=> '',//0 普通  1 销售 （''或者不传） 全部
		  "mobile"=>'23',//   ''或者不填  全部
		  "status"=> ''//0 正常  1  禁止  （''或者不传） 全部
        );
		*/
		//查看用户账号
		/*
		$url = "http://127.0.0.1/api/api.php?c=user&m=getUser";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "id"=>'',
		  "page"=>1,
		  "authTime"=>time()
        );
		*/
		//修改用户信息
		/*
		$url = "http://127.0.0.1/api/api.php?c=user&m=update";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "authTime"=>time(),
		  "id"=>3,
		  "fmobile"=>'123', //可填
		  "mobile"=>'321',  //可填
		  "pwd"=>'123456',  //可填
		  "uname"=>'aaa',   //可填
		  "image"=>'image', //可填
		  "isSaler"=>'1',   //0 普通  1  销售
		  "status"=>'1' //0  可用 1 禁用  2异常
		  
        );
		*/
		//删除用户信息
		/*
		$url = "http://127.0.0.1/api/api.php?c=user&m=delete";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "authTime"=>time(),
		  "id"=>10,
        );
		*/
		//添加user
		/*
		$url = "http://127.0.0.1/api/api.php?c=user&m=add";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "authTime"=>time(),
		  "mobile"=>'18222323233',
          "pwd" => "123456",
		  "uname"=>'uname',
		  "fmobile" => "fmobile",//可填
		  "ip" => "ip",//可填
		  "createTime" => "123123",//可填
		  "image" => "image",//可填
		  "isSaler" => "1" //0 普通  1 销售
        );
		*/
		//查看信用卡
		/*
		$url = "http://127.0.0.1/api/api.php?c=credit&m=getCredit";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "id"=>'',
		  "page"=>2,
		  "authTime"=>time()
        );
		*/
		//修改信用卡
		/*
		$url = "http://127.0.0.1/api/api.php?c=credit&m=update";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "authTime"=>time(),
		  "id"=>5,
		  "title"=>'信用卡2',
		  "image"=>'image2',
          "sketch" => "sketch2", //简要描述
		  "bank"=>'bank2',
		  "limit" => "10",//额度
		  "describe" => "describe2",//可填
		  "url" => "url2",//可填
		  "status" => 0//0 上架  1 下架
		  
        );
		*/
		//删除信用卡信息
		/*
		$url = "http://127.0.0.1/api/api.php?c=credit&m=delete";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "authTime"=>time(),
		  "id"=>10,
        );
		*/
		//添加信用卡
		/*
		$url = "http://127.0.0.1/api/api.php?c=credit&m=add";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
		  "auth" => $auth,
		  "authTime"=>time(),
		  "title"=>'信用卡',
		  "image"=>'image',
		  "sketch" => "sketch", //简要描述
		  "bank"=>'bank',
		  "limit" => "100",//额度
		  "describe" => "describe",//可填
		  "url" => "url"//可填
		  
		);
		*/
		//查看信用卡银行
		/*
		$url = "http://127.0.0.1/api/api.php?c=credit&m=getBank";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "authTime"=>time(),
        );
		*/
		//收索信用卡
		/*
		$url = "http://127.0.0.1/api/api.php?c=credit&m=search";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "authTime"=>time(),
		  "page"=>3,
		  "title"=> '',//卡名  模糊匹配
		  "bank"=>'',//   银行卡名字  精确匹配的
		  "status"=> ''//0 正常  1  禁止  （''或者不传） 全部
        );
		*/
		//收索贷款
		/*
		$url = "http://127.0.0.1/api/api.php?c=loan&m=search";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "authTime"=>time(),
		  "page"=>1,
		  "name"=> 'name',//卡名  模糊匹配
		  "label4"=>'',
		  "label6"=> '2',
		  "status"=>'0' //0 正常 1禁止 
        );
		*/
		//删除贷款信息
		/*
		$url = "http://127.0.0.1/api/api.php?c=loan&m=delete";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "authTime"=>time(),
		  "id"=>10,
        );
		*/
		//查看贷款
		/*
		$url = "http://127.0.0.1/api/api.php?c=loan&m=getLoan";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "id"=>'',
		  "page"=>1,
		  "authTime"=>time()
        );
		*/
		
		//修改贷款
		/*
		$url = "http://127.0.0.1/api/api.php?c=loan&m=update";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "authTime"=>time(),
		  "id"=>'1',
		  "image"=>'image',
		  "name"=>'name',
		  "minpay" => "222", //最小贷款金额
		  "maxpay"=>'3333',//最大贷款金额
		  "people" => "5",
		  "sketch" => "sketch",//简要描述
		  "label6" => "label6",//首页6个标签
		  "label4" => "label4",//标签 （最快，最少。。）
		  "consult" => "consult",//咨询
		  "maxPayDate" => "maxPayDate",//最快拨款时间
		  "minDate" => "1",//最短期限
		  "maxDate" => "2",//最长期限
		  "describe" => "describe",//描素
		  "require" => "require",
		  "strategy" => "strategy",
		  "other" => "other",
		  "url" => "url",
		  "strategy" => "strategy",
		  "other" => "other",
		  "status"=>"1"//0 正常 1 禁止
        );
		*/
		//添加贷款
		/*
		$url = "http://127.0.0.1/api/api.php?c=loan&m=add";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
		  "auth" => $auth,
		  "authTime"=>time(),
		  "image"=>'image',
		  "name"=>'name',
		  "minpay" => "1", //最小贷款金额
		  "maxpay"=>'2',//最大贷款金额
		  "people" => "5",
		  "sketch" => "sketch",//简要描述
		  "label6" => "label6",//首页6个标签
		  "label4" => "label4",//标签 （最快，最少。。）
		  "consult" => "consult",//咨询
		  "maxPayDate" => "maxPayDate",//最快拨款时间
		  "minDate" => "1",//最短期限
		  "maxDate" => "2",//最长期限
		  "describe" => "describe",//描素
		  "require" => "require",
		  "strategy" => "strategy",
		  "other" => "other",
		  "url" => "url",
		  "strategy" => "strategy",
		  "other" => "other"
		  
		);
		*/
		//删除新闻
		/*
		$url = "http://127.0.0.1/api/api.php?c=article&m=delete";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "authTime"=>time(),
		  "id"=>10,
        );
		*/
		//查看新闻
		/*
		$url = "http://127.0.0.1/api/api.php?c=article&m=getArticle";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "id"=>'',
		  "page"=>1,
		  "authTime"=>time()
        );
		*/
		//修改新闻
		/*
		$url = "http://127.0.0.1/api/api.php?c=article&m=update";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "authTime"=>time(),
		  "id"=>'1',
		  "auth" => $auth,
		  "authTime"=>time(),
		  "title"=>'title2',
		  "content"=>'content2',
		  "type" => "2", //1 news 2 ad
		  "image"=>'image2',//最大贷款金额
		  "describe" => "describ2e",
		  "label" => "2"
        );
		*/
		//添加新闻
		/*
		$url = "http://127.0.0.1/api/api.php?c=article&m=add";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
		  "auth" => $auth,
		  "authTime"=>time(),
		  "title"=>'title',
		  "content"=>'content',
		  "type" => "1", //1 news 2 ad
		  "image"=>'image',//最大贷款金额
		  "describe" => "describe",
		  "label" => "1"
		  
		);
		*/
		/*
		//上传图片
		http://127.0.0.1/api/api.php?c=upload&m=img
		*/
		//查看回馈
		/*
		$url = "http://127.0.0.1/api/api.php?c=feedback&m=getFeedback";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "id"=>'',
		  "page"=>1,
		  "authTime"=>time()
        );
		*/
		//修改回馈
		/*
		$url = "http://127.0.0.1/api/api.php?c=feedback&m=update";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "authTime"=>time(),
		  "id"=>'1',
		  "content"=>'二爷到此一游',
		  "mobile"=>'11111111',
		  "status"=>"1"//0 正常 1 禁止
        );
		*/
		//添加贷款
		/*
		$url = "http://127.0.0.1/api/api.php?c=feedback&m=add";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
		  "auth" => $auth,
		  "authTime"=>time(),
		  "content"=>'大爷到此一游',
		  "mobile"=>'18222323233'
		);
		*/
		//删除新闻
		/*
		$url = "http://127.0.0.1/api/api.php?c=feedback&m=delete";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "authTime"=>time(),
		  "id"=>5,
        );
		*/
		//查看客服
		/*
		$url = "http://127.0.0.1/api/api.php?c=customer&m=getCustomer";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "id"=>'',
		  "page"=>1,
		  "authTime"=>time()
        );
		*/
		//收索客服
		/*
		$url = "http://127.0.0.1/api/api.php?c=customer&m=search";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "id"=>'',
		  "page"=>1,
		  "type"=>1,
		  "authTime"=>time()
        );
		*/
		//修改客服
		/*
		$url = "http://127.0.0.1/api/api.php?c=customer&m=update";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "authTime"=>time(),
		  "id"=>'1',
		  "name"=>'22222',
		  "type"=>'2', // 1 微信  2 qq
		  "num"=>'22222222',
		  "status"=>"1"//0 正常 1 禁止
        );
		*/
		//添加客服
		/*
		$url = "http://127.0.0.1/api/api.php?c=customer&m=add";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
		  "auth" => $auth,
		  "authTime"=>time(),
		  "name"=>'鱼头坨',
		  "type"=>'1', // 1 微信  2 qq
		  "num"=>'443323432423'
		);
		*/
		//删除客服
		/*
		$url = "http://127.0.0.1/api/api.php?c=customer&m=delete";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "authTime"=>time(),
		  "id"=>5,
        );
		*/
		//修改贷款排序
		/*
		$url = "http://127.0.0.1/api/api.php?c=loan&m=sortById";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "authTime"=>time(),
		  "id"=>'1,2,3,4,5,6,7',
		  "sortId"=>'1,2,3,4,5,6,7'
        );
		*/
		//导出execl的mobile
		//$url = "http://127.0.0.1/api/api.php?c=download&m=execl";
		
		//搜索新闻
		$url = "http://127.0.0.1/api/api.php?c=article&m=search";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "title"=>'3',
		  "type"=>'2',
		  "page"=>'1',
		  "authTime"=>time()
        );
		`