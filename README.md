==============================================================================

  TexturePacker Exporter Plugin for OPTPiX SpriteStudio

  Copyright(C) 2013 Web Technology Corp.

==============================================================================

------------------------------------------------------------------------------
# �͂��߂�

�{�v���O�C���́ATexturePacker �ō쐬�����e�N�X�`���A�g���X��SpriteStudio��ssce
�`���ɕϊ�����TexturePacker�p�̃G�N�X�|�[�^�ł��B

Texture Packer�ŃA�g���X���쐬�����ۂɎg�p�����א؂��
�C���[�W��SpriteStudio�̃Z���Ƃ��Ďg�p�ł��܂��B

���̃v���O�C����Texture Packer�ɃC���X�g�[�����Ă��g�p���������܂��B

------------------------------------------------------------------------------
# �X�V����

1.0 (2013/9/26)
- ���񃊃��[�X

------------------------------------------------------------------------------
# �C���X�g�[���菇

1. Texture Packer���N�����܂��B

2. Texture Packer�̃��j���[���́uPreferences�v��I�т܂��B  
  (Windos�łł�Help���AMac�ł�TexturePacker���j���[���ɓ����Ă��܂��B�j

3. �G�N�X�|�[�^�̃t�H���_��I�����܂��B  
  [Preferences]�_�C�A���O����[Settings]�^�u���ɂ���A[Custom data exporters]��
  �G�N�X�|�[�^�̃v���O�C��������t�H���_��I�����܂��B

  ���̎��A�v���O�C���̃t�H���_�K�w�͉��L�̗l�ɂ��ĉ������B

 �@�@TexturePackerPlguins [��E�C��]  
 �@�@�@�@SpriteStudio  
 �@�@�@�@�@�@|-exporter.xml  
 �@�@�@�@�@�@|-template.xml

  ��Ƃ��Ď����Ă���uTexturePackerPlguins�v�t�H���_����L��[Custom data exporters]�t�H���_�I���e�L�X�g�{�b�N�X�֓��͂��܂��B

4. Texture Packer���ċN�����ĉ������B

�ȏ�� Output - Data Format�ցuSpriteStudio�v�`���̖��O���\������܂��B

------------------------------------------------------------------------------
# SpriteStudio �֎�荞�ނ��߂̎菇

1. �܂��p�b�L���O�ΏۂƂȂ�C���[�W��TexturePacker�֓o�^���A�e��ݒ��C�ӂ̒l��
  �ύX���܂��B

2. ��ʂ�̐ݒ肪����������AOutput �y�C���Ɉڂ�܂��B

3. Data Format �� SpriteStudio ��I�����܂��B

4. Data file name �ŏo�͂���Z���}�b�v�t�@�C��(.ssce) �̕ۑ���ƃt�@�C�������w��
  ���܂��B

5. Texture file �ŏo�͂���摜�t�@�C���̕ۑ���ƃt�@�C�������w�肵�܂��B

  �y�����ӁI�z
  �Z���}�b�v�A�o�͉摜�t�@�C���̕ۑ���t�H���_�́A���p����SpriteStudio�v���W�F
  �N�g�t�H���_�ȉ����w�肷��悤�ɂ��ĉ������B

6. Publish ���A�G���[���o�������������Ƃ��m�F���܂��B

7. SpriteStudio ���N�����A�ǉ���̃v���W�F�N�g���J������Ԃɂ��Ă����܂��B

8. �o�͂��ꂽ .ssce �t�@�C���� SpriteStudio �փh���b�v���邩�A�u�v���W�F�N�g�v��
  �j���[�́u�����t�@�C���̒ǉ��v���� .ssce �t�@�C����I�����܂��B

------------------------------------------------------------------------------
# ������

- TextuePacker ����o�͂��� .ssce �t�@�C���𐳂����ǂݍ��ނ��߂ɂ�
  SpriteStudio 5.1.0 �ȍ~�̃o�[�W�������K�v�ł��B

- ��x SpriteStudio �ɓǂݍ���ŁA�Q�ƃZ���L�[��ǉ�������ɁA�Y������Z���̌�
  �摜�̃t�@�C������ύX���A�ēx TexturePacker ���� Publish ����ƕύX�O�̖��O
  �����Z���������炸�A�A�j���[�V�������Q�Ƃ���Z����������ԂɂȂ�܂��B
  
  �����Ȃ����ꍇ�A�Y���̃Z�����w�肵�����K�v������܂��̂ł����Ӊ������B
  �p�[�c�̉摜�t�@�C�����͂Ȃ�ׂ����O�Ɋm�肵�Ă������������߂��܂��B

- Windows �� �� TexturePacker �ŏo�͂���ꍇ�A�S�p�����͎g���܂���B
  
  xml �t�@�C���� shift-jis �t�H�[�}�b�g�ɂȂ邽�߁AMac ��SpriteStudio �ƌ݊���
  ���ۂĂȂ��������R�ł��B
  
  ���o�͂��ꂽ .ssce �t�@�C���̃w�b�_�ɂ��� encoding="utf-8" ��
    encoding="shift-jis" �ɏ������������ Windows �� SpriteStudio �ɓǂݍ����
    �㏑���ۑ������ utf-8 �ɕϊ�����AMac ��SpriteStudio�ł��ǂݍ��߂�悤�ɂ�
    ��܂��B
  
  ��Mac �� TexturePacker �ŕۑ������ꍇ�AUTF-8 �ɂȂ邽�߁ASpriteStudio �ɖ��
    �Ȃ��ǂݍ��߂܂��B

- FixedSize, MaxSize ���z���ăG���A�O�ƂȂ�摜�t�@�C���������Ԃ� Publish ��
  �ꂽ ssce �� SpriteStudio �ɓǂݍ��߂܂���B



==============================================================================
������ЃE�F�u�e�N�m���W  
http://www.webtech.co.jp/  
Copyright(C) 2013 Web Technology Corp.  
==============================================================================

* OPTPiX SpriteStudio, Web Technology�́A������ЃE�F�u�e�N�m���W�̓o�^���W�ł��B
* ���̑��̏��i���͊e�Ђ̓o�^���W�܂��͏��W�ł��B

[End of TEXT]
