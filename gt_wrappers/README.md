
## In progress!!

point db_root_dir to the DBs

coco_api in db_root_dir('COCO')


To create a gt_sets file:


ls image_folder > tmp.txt
sed -e 's/.jpg//g' -i tmp.txt > gt_set_ids.txt
