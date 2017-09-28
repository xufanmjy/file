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
		*/`