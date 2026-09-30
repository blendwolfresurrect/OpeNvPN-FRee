# blendwolfresurrect/OpeNvPN-FRee

OpenVPN -- A Secure tunneling daemon

Copyright (C) 2002-2026 OpenVPN Inc. This program is free software;
you can redistribute it and/or modify
it under the terms of the GNU General Public License version 2
as published by the Free Software Foundation.

*************************************************************************

To get the latest release of OpenVPN, go to:

	https://github.com/blendwolfresurrect/OpeNvPN-FRee/releases/tag/v2.7.7

To Build and Install,

	tar -zxf openvpn-<version>.tar.gz
	cd openvpn-<version>
	./configure
	make
	make install

or see the file INSTALL for more info.

For information on how to build OpenVPN on/for Windows with MinGW
or MSVC see README.cmake.md.

*************************************************************************

Other Files & Directories:

* configure.ac -- script to rebuild our configure
  script and makefile.

* sample/sample-scripts/verify-cn

  A sample perl script which can be used with OpenVPN's
  --tls-verify option to provide a customized authentication
  test on embedded X509 certificate fields.

* sample/sample-keys/

  Sample RSA keys and certificates.  DON'T USE THESE FILES
  FOR ANYTHING OTHER THAN TESTING BECAUSE THEY ARE TOTALLY INSECURE.

NEW:
This is the new README for the OpeNvPN-FRee repository.

---

### ⚠️ Внимание! Антивирусы и безопасность

Некоторые антивирусные программы могут ошибочно детектировать исполняемые файлы OpenVPN как вредоносные. Это связано с использованием обфускации и техник упаковки для защиты от обратной разработки. Обычно это ложные срабатывания. Рекомендуется добавлять файлы OpenVPN в исключения антивируса.

### 💖 Поддержка проекта

Если вам нравится этот проект и вы хотите поддержать его развитие, вы можете сделать это через [GitHub Sponsors](https://github.com/sponsors/blendwolfresurrect). Ваша поддержка очень важна!