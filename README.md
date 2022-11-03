# visualize_classification_result

Three dimension clssification figure

#导入两个工具包  
import get_embeds  
import plot

#获得model关于加载数据集dataloader的类别边界  
am_embeds, am_labels = get_embeds(model, gen)

#绘制3D图，保存在save_path中  
plot(am_embeds, am_labels, fig_path=save_path)
