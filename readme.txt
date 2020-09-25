This tool has only 1 function now. It converts any colour(colour A) to colour B. Colour A could be any random colour, while colour B is from a user defined colour table. The result colour B is the nearest colour from A. Means this tool converts colour into a colour table according to the distance between the random colour and any colour within the table.

The pseudo code looks like:

question_colour(random_colour)
colour_table(user defined colour table)
distances(question_colour, elements in colour_table)
result_colour = colour_table[min_element(distances)]

In real code, it builds up some new table for a fast query. In fact the code needs 10ish seconds to build up the table, after that, it could be very fast converting.
This tool could help anything which needs converting random colour into a specific set of colours. Gif algo, embroidery, etc.
Also, I have a discord. Reporting, suggestions, chatting are all welcomed.





������ߵ������ǣ����κ���ɫת����һ���ض�����ɫ�������ĳ����ɫ����������κ���ɫ�������յĽ����ɫ���Ǿ�����С�ġ�
���ѱ�
��ô˵��
question_colour(random_colour)
colour_table(user defined colour table)
distances(question_colour, elements in colour_table)
result_colour = colour_table[min_element(distances)]

������һЩ����������һ����ѯ�������ѯ����Էǳ����ٵĲ��ҵ��𰸡�����������ռ��10m���ҵ��ڴ棬������ѯ���ʱ������10�����ң�֮����ͼƬ��ʱ�䣨��4096x4096�ֱ��ʼ��㣩������0.1�����ҡ��ǳ��졣

��������Ǹ�һλ��ͼ��ѹ���㷨�о�������д�ġ����幦����ȫ��������Ҫ�����ġ��������ϣ������������ϼ����Ĺ��ܣ��������ҵ�discord����˵����ʱ��Ļ�Ҳ�ᾡ�����Կ���

