# ��ά��js���ɿ�
���ַ������ɶ�ά�룬����Base64������ʽ���

## �÷�
    jrQrcode.getQrBase64(text, options);
    @param: text: Ҫ���ɶ�ά����ַ���֧������
    @param: options: {
        padding		: 10,   //��ά���ı߿հף�Ĭ��Ϊ10px
        width		: 256,  //��ά��ͼƬ��ȣ�Ĭ��Ϊ256px
        height		: 256,  //��ά��ͼƬ�߶ȣ�Ĭ��Ϊ256px
        correctLevel	: QRErrorCorrectLevel.H,    //��ά���ݴ�level��Ĭ��Ϊ��
        background      : "#ffffff",    //��ά����ɫ
        foreground      : "#000000"     //��ά�뱳����ɫ
    }
    @return: ���ɵĶ�ά��Base64�ַ���

## ��ά���ݴ���
    var QRErrorCorrectLevel = {
    	L : 1,
    	M : 0,
    	Q : 3,
    	H : 2
    };
