����Scrapy��ܵ�����ϵͳ����ȡ����ͼ��Top250����ȡ�����������ߡ������硢����ʱ�䡢�۸����֡��������������䡢�������Ϣ��
spider_xpath�����б�д�Ĵ����࣬�ⲿ�ֵĴ�����Ҫ��ɽ���response����ȡitem
1. �Գ�ʼ��URLRequest, �����ûص�����, ����requeset������ϲ�����ʱ, ������response, ����Ϊ�������ݸ��ص�����. spider�г�ʼ��request��ͨ��start_requests()����ȡ�ġ�start_requests()��ȡstart_urls�е�URL, ����parse�Իص���������Request
��2. �ڻص������ڷ������ص���ҳ����, ���Է���item�������Request�����ص�Request����֮��ᾭ��Scrapy����, ������Ӧ������, ���������õ�callback����.
��3. �ڻص�����, ͨ��xpath, css�ȷ�����ȡ������Ҫ����������item
��4. ���item���͸�pipeline����

items���������鼮��Ϣ��item
middlewares���м������������
pipelines����Item ��Spider�б��ռ�֮�󣬾ͻᱻ���ݵ�Item Pipeline�н��д���ÿ��item pipeline�����ʵ���˼򵥵ķ�����python�࣬������յ�item��ͨ����ִ��һЩ��Ϊ��ͬʱҲ������Item�Ƿ����ͨ��pipeline,���߱����������ٽ��д���
item pipeline����Ҫ���ã�
1.����html����
2.��֤��ȡ������
3.ȥ�ز�����
4.����ȡ�Ľ�����浽���ݿ��л��ļ���

