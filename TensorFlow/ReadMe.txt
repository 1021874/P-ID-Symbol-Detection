cd C:\TensorFlow\scripts\preprocessing

Update C:\TensorFlow\workspace\training_demo\annotations\label_map,pbtxt file
Open C:\TensorFlow\models\my_ssd_mobilenet_v2_fpnlite\pipeline.config make changes


cd C:\TensorFlow\workspace\training_demo
python model_main_tf2.py --model_dir=models\my_ssd_mobilenet_v2_fpnlite --pipeline_config_path=models\my_ssd_mobilenet_v2_fpnlite\pipeline.config