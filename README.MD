# zoomeye-phpsdk
��װ��zoomeye��php�汾sdk,������
* һ��php�汾��zoomeye��sdk
* �����ʺ����뼴�ɿ���ʹ�õ�ʾ������
* �Զ�����session
* �쳣�����Լ������Ĵ��������ʾ



# ���ٿ�ʼ
``` .cfg
�޸�������û������� ͬʱ��sessiontime����Ϊ0 ���� 
```

# SDK
getResourcesInfo
------------
��ȡ��ǰ�ʺ�ʹ�õ�Ȩ��

searchHost
------------
��ѯ����

searchWeb
------------
��ѯ��վ

getLastError
------------
���һ��ִ�еĴ���

# ע������ 
��Ҫʹ��curl
------------
 * ��Ҫʹ��curl��
 * windows�¿���������
 * ����PHPĿ¼�е�libeay32.dll, ssleay32.dll, php5ts.dll, php_curl.dll�ļ��� system32 Ŀ¼��(php_curl.dl��ext�ļ���)
 * �޸�php.ini�����ú�extension_dir��ȥ��extension = php_curl.dllǰ��ķֺš�
 * ����apache����IIS��
 * linux�¿���������
 * ��װcURL
 * # wgethttp://curl.haxx.se/download/curl-7.17.1.tar.gz
 * # tar -zxf curl-7.17.1.tar.gz
 * # ./configure --prefix=/usr/local/curl
 * # make; make install
 * ��װphp
 * �򿪿��� --with-curl=/usr/local/curl
 