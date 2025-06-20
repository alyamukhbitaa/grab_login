# -*- coding: utf-8 -*-

from PyQt6 import QtCore, QtGui, QtWidgets

class Ui_Form(object):
    def setupUi(self, Form):
        Form.setObjectName("Form")
        Form.resize(323, 441)
        Form.setMinimumSize(QtCore.QSize(323, 441))
        Form.setStyleSheet("background-color: #00B14F;")

        self.label = QtWidgets.QLabel(Form)
        self.label.setGeometry(QtCore.QRect(50, 0, 221, 1))
        self.label.setText("")
        self.label.setPixmap(QtGui.QPixmap("C:/Users/lenovo/Downloads/grab.logo.jpg"))
        self.label.setScaledContents(True)
        self.label.setWordWrap(False)
        self.label.setObjectName("label")

        self.label_2 = QtWidgets.QLabel(Form)
        self.label_2.setGeometry(QtCore.QRect(40, 70, 271, 41))
        font = QtGui.QFont()
        font.setFamily("Segoe UI")
        font.setPointSize(11)
        font.setBold(False)
        font.setWeight(50)
        self.label_2.setFont(font)
        self.label_2.setStyleSheet("color: white;")
        self.label_2.setObjectName("label_2")

        self.pushButton = QtWidgets.QPushButton(Form)
        self.pushButton.setGeometry(QtCore.QRect(50, 240, 211, 31))
        self.pushButton.setStyleSheet("""
            color: white;
            background-color: #DB4437;
            font-weight: bold;
            padding: 8px;
            border-radius: 6px;
        """)
        icon = QtGui.QIcon()
        icon.addPixmap(
            QtGui.QPixmap("C:/Users/lenovo/Downloads/icon.google.jpeg"),
            QtGui.QIcon.Mode.Normal,
            QtGui.QIcon.State.Off
        )
        self.pushButton.setIcon(icon)
        self.pushButton.setObjectName("pushButton")

        self.pushButton_2 = QtWidgets.QPushButton(Form)
        self.pushButton_2.setGeometry(QtCore.QRect(50, 290, 211, 31))
        self.pushButton_2.setStyleSheet("""
            color: white;
            background-color: #4267B2;
            font-weight: bold;
            padding: 8px;
            border-radius: 6px;
        """)
        icon1 = QtGui.QIcon()
        icon1.addPixmap(
            QtGui.QPixmap("C:/Users/lenovo/Downloads/icon.fb.jpeg"),
            QtGui.QIcon.Mode.Normal,
            QtGui.QIcon.State.Off
        )
        self.pushButton_2.setIcon(icon1)
        self.pushButton_2.setObjectName("pushButton_2")

        self.pushButton_3 = QtWidgets.QPushButton(Form)
        self.pushButton_3.setGeometry(QtCore.QRect(50, 380, 221, 31))
        self.pushButton_3.setStyleSheet("""
            color: white;
            background-color: #4A4A4A;
            font-weight: bold;
            padding: 8px;
            border-radius: 6px;
        """)
        icon2 = QtGui.QIcon()
        icon2.addPixmap(
            QtGui.QPixmap("C:/Users/lenovo/Downloads/icon.hp.webp"),
            QtGui.QIcon.Mode.Normal,
            QtGui.QIcon.State.Off
        )
        self.pushButton_3.setIcon(icon2)
        self.pushButton_3.setObjectName("pushButton_3")

        self.label_4 = QtWidgets.QLabel(Form)
        self.label_4.setGeometry(QtCore.QRect(90, 10, 141, 61))
        self.label_4.setText("")
        self.label_4.setPixmap(QtGui.QPixmap("C:/Users/lenovo/Downloads/logo.grab2.jpg"))
        self.label_4.setScaledContents(True)
        self.label_4.setObjectName("label_4")

        self.label_3 = QtWidgets.QLabel(Form)
        self.label_3.setGeometry(QtCore.QRect(140, 340, 31, 16))
        font = QtGui.QFont()
        font.setPointSize(9)
        font.setBold(True)
        font.setWeight(75)
        self.label_3.setFont(font)
        self.label_3.setStyleSheet("color: white; background: transparent; border: none; font-weight: bold;")
        self.label_3.setObjectName("label_3")

        self.frame = QtWidgets.QFrame(Form)
        self.frame.setGeometry(QtCore.QRect(180, 350, 101, 80))
        self.frame.setStyleSheet("border-top: 1px solid white; background: transparent;")
        self.frame.setFrameShape(QtWidgets.QFrame.Shape.StyledPanel)
        self.frame.setFrameShadow(QtWidgets.QFrame.Shadow.Raised)
        self.frame.setObjectName("frame")

        self.frame_2 = QtWidgets.QFrame(Form)
        self.frame_2.setGeometry(QtCore.QRect(30, 350, 101, 20))
        self.frame_2.setStyleSheet("border-top: 1px solid white; background: transparent;")
        self.frame_2.setFrameShape(QtWidgets.QFrame.Shape.HLine)
        self.frame_2.setFrameShadow(QtWidgets.QFrame.Shadow.Plain)
        self.frame_2.setLineWidth(1)
        self.frame_2.setObjectName("frame_2")

        self.retranslateUi(Form)
        QtCore.QMetaObject.connectSlotsByName(Form)

    def retranslateUi(self, Form):
        _translate = QtCore.QCoreApplication.translate
        Form.setWindowTitle(_translate("Form", "Form"))
        self.label_2.setText(_translate("Form", "Satu aplikasi untuk semua kebutuhan \n                       harianmu"))
        self.pushButton.setText(_translate("Form", "   Lanjutkan dengan Google"))
        self.pushButton_2.setText(_translate("Form", "  Lanjutkan dengan Facebook"))
        self.pushButton_3.setText(_translate("Form", "Lanjutkan dengan Nomor Ponsel"))
        self.label_3.setText(_translate("Form", "atau"))

if __name__ == "__main__":
    import sys
    app = QtWidgets.QApplication(sys.argv)
    Form = QtWidgets.QWidget()
    ui = Ui_Form()
    ui.setupUi(Form)
    Form.show()
    sys.exit(app.exec())
