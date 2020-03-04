# generative_model
Generative Model for De Novo Drug Design

##（一）使用生成网络生成新的化合物、化合物文库。
###（1）将分子描述作为输入随机生成相似的新分子（如smiles、分子指纹）
分别举例使用RNN、VAE、GAN等模型的案例。
###（2）生成分子图结构（molecular graph）。
由于smiles的局限性：smiles不能捕捉分子之间的结构相似性；一个分子可以有多个smiles表示；导致生成的分子缺乏多样性和有效性。直接采用图来表示分子。
##（二）扩展到条件分子设计。
除了生成大量与输入相似的新分子，还可以进一步通过生成模型的潜在空间与性能预测模块相结合，生成性能接近预定目标条件的新分子。
##（三）生成肽段、蛋白质。
如ProteinGAN
