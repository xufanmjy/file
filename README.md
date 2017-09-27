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
		  "uid"=>'18', //可填
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
		  "uid"=>18,
		  "fid"=>'1', //可填
		  "mobile"=>'321',  //可填
		  "pwd"=>'123456',  //可填
		  "uname"=>'aaa',   //可填
		  "image"=>'image', //可填	  
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
		  "uid"=>18,
        );
		*/
		
		//查看用户账号
		/*
		$url = "http://127.0.0.1/api/api.php?c=user&m=getUser";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "uid"=>'',
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
		  "uid"=>9,
		  "fmobile"=>'123', //可填
		  "mobile"=>'321',  //可填
		  "pwd"=>'123456',  //可填
		  "uname"=>'aaa',   //可填
		  "image"=>'image', //可填
		  "isSaler"=>'1'   //0 普通  1  销售
		  
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
		  "uid"=>10,
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
		  "id"=>'5',
		  "page"=>1,
		  "authTime"=>time()
        );
		*/
		//修改用户信息
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
		  "url" => "url2"//可填
		  
        );
		*/
		//删除用户信息
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
		  "limit" => "limit",//额度
		  "describe" => "describe",//可填
		  "url" => "url"//可填
		  
        );
		*/`