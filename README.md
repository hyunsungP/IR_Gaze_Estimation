20172258, IMLAB Dongmin Cha

-TRAINING from Scratch-
bin\caffe train --solver=ir_gaze_solver.prototxt --gpu=0

-TRAINING from Weights-
bin\caffe train --solver=ir_gaze_solver.prototxt --weights=caffemodels/***.caffemodel --gpu=0