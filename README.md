		`						Api�ĵ�
		//��¼
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
		//���admin
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
		//�鿴admin
		/*
		$url = "http://127.0.0.1/api/api.php?c=admin&m=getUser";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "id"=>'18', //����
		  "page"=>1,
		  "authTime"=>time()
        );
		*/
		//�޸�admin
		/*
		$url = "http://127.0.0.1/api/api.php?c=admin&m=update";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "authTime"=>time(),
		  "id"=>18,
		  "fid"=>'1', //����
		  "mobile"=>'321',  //����
		  "pwd"=>'123456',  //����
		  "uname"=>'aaa',   //����
		  "image"=>'image', //����	  
		  "status"=>'1' //0  ���� 1 ����  2�쳣
        );
		*/
		//ɾ��admin
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
		//�����û��˺�
		/*
		$url = "http://127.0.0.1/api/api.php?c=user&m=search";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "authTime"=>time(),
		  "page"=>'1',
		  "isSaler"=> '',//0 ��ͨ  1 ���� ��''���߲����� ȫ��
		  "mobile"=>'23',//   ''���߲���  ȫ��
		  "status"=> ''//0 ����  1  ��ֹ  ��''���߲����� ȫ��
        );
		*/
		//�鿴�û��˺�
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
		//�޸��û���Ϣ
		/*
		$url = "http://127.0.0.1/api/api.php?c=user&m=update";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "authTime"=>time(),
		  "id"=>3,
		  "fmobile"=>'123', //����
		  "mobile"=>'321',  //����
		  "pwd"=>'123456',  //����
		  "uname"=>'aaa',   //����
		  "image"=>'image', //����
		  "isSaler"=>'1',   //0 ��ͨ  1  ����
		  "status"=>'1' //0  ���� 1 ����  2�쳣
		  
        );
		*/
		//ɾ���û���Ϣ
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
		//���user
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
		  "fmobile" => "fmobile",//����
		  "ip" => "ip",//����
		  "createTime" => "123123",//����
		  "image" => "image",//����
		  "isSaler" => "1" //0 ��ͨ  1 ����
        );
		*/
		//�鿴���ÿ�
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
		//�޸����ÿ�
		/*
		$url = "http://127.0.0.1/api/api.php?c=credit&m=update";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "authTime"=>time(),
		  "id"=>5,
		  "title"=>'���ÿ�2',
		  "image"=>'image2',
          "sketch" => "sketch2", //��Ҫ����
		  "bank"=>'bank2',
		  "limit" => "10",//���
		  "describe" => "describe2",//����
		  "url" => "url2",//����
		  "status" => 0//0 �ϼ�  1 �¼�
		  
        );
		*/
		//ɾ�����ÿ���Ϣ
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
		//������ÿ�
		/*
		$url = "http://127.0.0.1/api/api.php?c=credit&m=add";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
		  "auth" => $auth,
		  "authTime"=>time(),
		  "title"=>'���ÿ�',
		  "image"=>'image',
		  "sketch" => "sketch", //��Ҫ����
		  "bank"=>'bank',
		  "limit" => "100",//���
		  "describe" => "describe",//����
		  "url" => "url"//����
		  
		);
		*/
		//�鿴���ÿ�����
		/*
		$url = "http://127.0.0.1/api/api.php?c=credit&m=getBank";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "authTime"=>time(),
        );
		*/
		//�������ÿ�
		/*
		$url = "http://127.0.0.1/api/api.php?c=credit&m=search";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "authTime"=>time(),
		  "page"=>3,
		  "title"=> '',//����  ģ��ƥ��
		  "bank"=>'',//   ���п�����  ��ȷƥ���
		  "status"=> ''//0 ����  1  ��ֹ  ��''���߲����� ȫ��
        );
		*/
		//��������
		/*
		$url = "http://127.0.0.1/api/api.php?c=loan&m=search";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "authTime"=>time(),
		  "page"=>1,
		  "name"=> 'name',//����  ģ��ƥ��
		  "label4"=>'',
		  "label6"=> '2',
		  "status"=>'0' //0 ���� 1��ֹ 
        );
		*/
		//ɾ��������Ϣ
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
		//�鿴����
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
		
		//�޸Ĵ���
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
		  "minpay" => "222", //��С������
		  "maxpay"=>'3333',//��������
		  "people" => "5",
		  "sketch" => "sketch",//��Ҫ����
		  "label6" => "label6",//��ҳ6����ǩ
		  "label4" => "label4",//��ǩ ����죬���١�����
		  "consult" => "consult",//��ѯ
		  "maxPayDate" => "maxPayDate",//��첦��ʱ��
		  "minDate" => "1",//�������
		  "maxDate" => "2",//�����
		  "describe" => "describe",//����
		  "require" => "require",
		  "strategy" => "strategy",
		  "other" => "other",
		  "url" => "url",
		  "strategy" => "strategy",
		  "other" => "other",
		  "status"=>"1"//0 ���� 1 ��ֹ
        );
		*/
		//��Ӵ���
		/*
		$url = "http://127.0.0.1/api/api.php?c=loan&m=add";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
		  "auth" => $auth,
		  "authTime"=>time(),
		  "image"=>'image',
		  "name"=>'name',
		  "minpay" => "1", //��С������
		  "maxpay"=>'2',//��������
		  "people" => "5",
		  "sketch" => "sketch",//��Ҫ����
		  "label6" => "label6",//��ҳ6����ǩ
		  "label4" => "label4",//��ǩ ����죬���١�����
		  "consult" => "consult",//��ѯ
		  "maxPayDate" => "maxPayDate",//��첦��ʱ��
		  "minDate" => "1",//�������
		  "maxDate" => "2",//�����
		  "describe" => "describe",//����
		  "require" => "require",
		  "strategy" => "strategy",
		  "other" => "other",
		  "url" => "url",
		  "strategy" => "strategy",
		  "other" => "other"
		  
		);
		*/
		//ɾ������
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
		//�鿴����
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
		//�޸�����
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
		  "image"=>'image2',//��������
		  "describe" => "describ2e",
		  "label" => "2"
        );
		*/
		//�������
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
		  "image"=>'image',//��������
		  "describe" => "describe",
		  "label" => "1"
		  
		);
		*/
		/*
		//�ϴ�ͼƬ
		http://127.0.0.1/api/api.php?c=upload&m=img
		*/
		//�鿴����
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
		//�޸Ļ���
		/*
		$url = "http://127.0.0.1/api/api.php?c=feedback&m=update";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "authTime"=>time(),
		  "id"=>'1',
		  "content"=>'��ү����һ��',
		  "mobile"=>'11111111',
		  "status"=>"1"//0 ���� 1 ��ֹ
        );
		*/
		//��Ӵ���
		/*
		$url = "http://127.0.0.1/api/api.php?c=feedback&m=add";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
		  "auth" => $auth,
		  "authTime"=>time(),
		  "content"=>'��ү����һ��',
		  "mobile"=>'18222323233'
		);
		*/
		//ɾ������
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
		//�鿴�ͷ�
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
		//�����ͷ�
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
		//�޸Ŀͷ�
		/*
		$url = "http://127.0.0.1/api/api.php?c=customer&m=update";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "authTime"=>time(),
		  "id"=>'1',
		  "name"=>'22222',
		  "type"=>'2', // 1 ΢��  2 qq
		  "num"=>'22222222',
		  "status"=>"1"//0 ���� 1 ��ֹ
        );
		*/
		//��ӿͷ�
		/*
		$url = "http://127.0.0.1/api/api.php?c=customer&m=add";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
		  "auth" => $auth,
		  "authTime"=>time(),
		  "name"=>'��ͷ��',
		  "type"=>'1', // 1 ΢��  2 qq
		  "num"=>'443323432423'
		);
		*/
		//ɾ���ͷ�
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
		//�޸Ĵ�������
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
		//����execl��mobile
		//$url = "http://127.0.0.1/api/api.php?c=download&m=execl";
		
		//��������
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