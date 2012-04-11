# AS3-obfuscator

��� ���������� �� PHP 5 � ����������� �� ���������� ���������� (�������� preg_*) ������� ���������� ��� ���� ������� �� ActionScript 3. 

�� �������� ����� ������� � ������� � ���� ������� �� ��������� ������ ��� ����������� ������ ������ ���������.


## ��� ��� ��������

- ������ ��������� (��� ������, � �������) � proc/source. 

- ��������� index.php.

- � ������ ��������� �������������� �������� ���������� ��������� �����/�����/����� �� ������ (��� ����������, �� ������� �����), ����, ������� ����� � proc/destination.


### ����������

- ���� ��� ������ (� ��� �����������) �� ����� �������������, ��������, ����� ��������� ����� (������, Main.as) ������������������ �� *.fla, �� ����������� ��� � ������ � �������� ������� ��������� (� index.php):
  
  <code>$aIgnoreWords = array_merge(AS3Validator::getReservedWords(), array("Main"));</code>
  
  ����� ��� ��������� ������ � ��������� ����.
  
- ���� �������������� ������� ����� proc/destination �� ������������, �������, ��� ����� ������������ ������ *.as (�� proc/source), � ������� ������ ������������ ������� ��� md5, ������ ���������� ��������.