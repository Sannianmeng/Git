Git is a distributed version control system.
Git is free software distributed under the GPL.
Git has a mutable index called stage.
Git tracks changes.
Git tracks changes of files.


 git add readmes.txt --->���޸ĵ��ļ�����ݴ�����
 git commit-m "readmes" --->���ݴ������ļ��ύ
 cat readmes.txt ----->�鿴�ļ������ݣ�
 git status ------>�鿴�ļ���״̬�������ݴ�������δ���ݴ��������ύ�ˣ�
 git checkout -- readme.txt ----->�����������������޸ģ�

����git checkout -- readme.txt��˼���ǣ���readme.txt�ļ��ڹ��������޸�ȫ�����������������������

һ����readme.txt���޸ĺ�û�б��ŵ��ݴ��������ڣ������޸ľͻص��Ͱ汾��һģһ����״̬��

һ����readme.txt�Ѿ���ӵ��ݴ������������޸ģ����ڣ������޸ľͻص���ӵ��ݴ������״̬��

��֮������������ļ��ص����һ��git commit��git addʱ��״̬

git checkout -- file�����е�--����Ҫ��û��--���ͱ���ˡ��л�����һ����֧������������ں���ķ�֧�����л��ٴ�����git checkout���

Gitͬ���������ǣ�������git reset HEAD file���԰��ݴ������޸ĳ�������unstage�������·Żع�������

git reset����ȿ��Ի��˰汾��Ҳ���԰��ݴ������޸Ļ��˵�����������������HEADʱ����ʾ���µİ汾��


��������ѡ��һ��ȷʵҪ�Ӱ汾����ɾ�����ļ����Ǿ�������git rmɾ��������git commit ���ļ��ʹӰ汾���б�ɾ���ˡ�

��һ�������ɾ���ˣ���Ϊ�汾���ﻹ���أ����Կ��Ժ����ɵذ���ɾ���ļ��ָ������°汾��

$ git checkout -- test.txt��


����git rm����ɾ��һ���ļ������һ���ļ��Ѿ����ύ���汾�⣬��ô����Զ���õ�����ɾ������ҪС�ģ���ֻ�ָܻ��ļ������°汾����ᶪʧ���һ���ύ�����޸ĵ����ݡ�
