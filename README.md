# 3D_FUSION_SPECTMPI_CTA
SPECTMPI AND CTA 3D FUSION TEST

现在使用 `from vtkmodules.qt.QVTKRenderWindowInteractor import QVTKRenderWindowInteractor` 导入模块，不再使用之前的 `from vtk.qt.QVTKRenderWindowInteractor import QVTKRenderWindowInteractor`

用户想设计一个软件来实现SPECT心肌灌注显像与CTA冠脉序列的配准和分割，并将二者三维结合呈现。用户目前有冠状动脉CTA数据和SPECT心肌灌注数据，已经在3D Slicer中完成了配准，并进行了冠状动脉和左心室心肌的分割。用户希望设计一个程序，在VSCode中实现3排3列的可视化布局：第一排显示CTA数据的冠状位、矢状位、横断位；第二排显示色阶显示的SPECT数据的冠状位、矢状位、横断位；第三排显示CTA和SPECT数据融合的冠状位、矢状位、横断位。用户希望将程序分成多个精细的.py文件实现，并且在后续添加旋转、缩放、平移等按钮功能。用户还希望在实现的界面中能够通过将CTA文件拖动到CTA所在一排的任意窗口中来打开CTA数据，并且三个窗口同步显示CTA图像，在最下方只显示一行文件路径；将SPECT文件拖动到SPECT所在排任意窗口中来打开SPECT数据，第三排同步显示CTA和SPECT数据的融合。暂时不涉及3D显示的问题。
