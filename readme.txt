�˰汾���ִ��뻹û�����Ż���

ʹ��˵����
1�����ڴ��뻹δ�Ż�������ԭʼ��nii�ļ�����Ҫ�ֽ���ָ��64*64*64��patch�洢����������ֱ�Ӷ�ȡ�洢�õ�patch�ļ���
2������ʹ�õ����ݼ��Ƚ��٣���Ҫ�����ݽ���data augmentation������matlab�ļ�data_augmentation��ԭʼ��niiͼ���ļ����з�ת����ת�������ݼ��ϣ���������֮����ļ�����������
3��fFindImageBoundaryCoordinate3D.py�ļ� �Ǹ���label��ֵ��ԭʼͼ���е�boundingbox�ָ��������֤�ָ������patch���ܰ���һ����label����
4��prepare_data.py �����ṩ���������Խ�ԭʼniiͼ���boundingbox�洢���������ָ��patch�洢������
5��GetData_new.py �ṩ���������粻������feed patch���Լ�˳���feed patch��
6��U_net_3D_multiLabels.py ��������庯��������ѵ��ʱ�ϵ㱣���Լ�tensorBoard�鿴��Output�ļ��� �洢����Ĳ����ļ�������ʹ������Ķϵ��ļ�������û�н�����ѵ���� log��tensorBoard��Ҫ���ļ��Ĵ洢Ŀ¼������ʹ��Output�ļ����е��Ѿ�ѵ���õĲ������ָ�http://www.sdspeople.fudan.edu.cn/zhuangxiahai/0/mmwhs/  �е�MRI ����
7��U_net_3D_Test_multiLabels.py�ļ��� ����ѵ���õ����磬������whole heart ��label��ͬ����Ҫ�Ƚ�ԭʼnii�ָ��patch��
8��U_net_3D_Test_multiLabels.py �Ὣ���е�patch��Ӧ��label�洢�������������Ҫ��patch����ƴ��������
9��make_whole_multiLabels.py ������ֵ�жϣ���8��label�ֱ𱣴��8��nii�ļ�������ÿһ���ļ���Ӧheart��һ��label
10.asemble.py���Ǹ���majority voting��ԭ�򣬽�8��label�ϲ���һ��whole heart��ͬʱʹ������ͨ���жϣ�ֻ����ÿһ��label�����Ĳ��֣�ȥ����С��islands��