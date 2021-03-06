# IR {docsify-ignore-all}

<div class="badge badge-pill badge-primary product_sku_tag">SKU:U002</div>

<div class="product_pic"><img src="assets/img/product_pics/unit/M5GO_Unit_ir.webp"></div>

## 描述

**IR** 是一款红外光电对管 Unit，集成了红外发射、接收管.通过GROVE接口与M5Core进行连接并控制红外发射、接收.支持红外编码、红外解码.

基于它可靠的短距离传输特性，在日常生活中，红外遥控广泛应用家电与消费类电子产品.

## 产品特性

- 1x 红外发射器
- 1x 红外接收器
- 距离范围: < 5m
- 开发平台: Arduino, UIFlow(Blockly,Python)
- 2x LEGO 兼容孔

## 包含

- 1x IR Unit
- 1x Grove 线

## EasyLoader

<img src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/image/EasyLoader_logo.webp" width="100px" style="margin-top:20px">

<a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/EasyLoader/Unit/EasyLoader_IR.exe"><button type="button" class="btn btn-primary">点击下载EasyLoader</button></a>

>1.EasyLoader是一个简洁快速的程序烧录器，每一个产品页面里的EasyLoader都提供了一个与产品相关的案例程序，通过简单步骤将其烧录至主控，能够进行一系列的功能验证.

>2.下载软件后，双击运行应用程序，将M5设备通过数据线连接至电脑,选择端口参数，点击 **"Burn"** 即可开始烧录.(**为M5StickC烧录时，请将波特率设置在750000或115200**)

?>3.目前EasyLoader仅适用于Windows操作系统、兼容M5体系采用ESP32作为控制核心的主机.在为M5Core烧录前需要安装CP210X驱动程序（使用M5StickC作为控制器的则无需安装）[点击此处查看驱动安装教程](zh_CN/related_documents/M5Burner#安装串口驱动)

## 案例程序

### 1. Arduino IDE

- [请点击此处下载Arduino示例程序](https://github.com/m5stack/M5Stack/tree/master/examples/Unit/IR)

### 2. UIFlow

- [请点击此处下载UIFlow](https://github.com/m5stack/M5-ProductExampleCodes/tree/master/Unit/IR/UIFlow)

<img src="assets/img/product_pics/unit/unit_example/IR/example_unit_ir_03.webp">

## 原理图

<img src="assets/img/product_pics/unit/ir_sch.JPG">

### 管脚映射

<table>
 <tr><td>M5Core(GROVE B)</td><td>GPIO36</td><td>GPIO26</td><td>5V</td><td>GND</td></tr>
 <tr><td>IR Unit</td><td>Receiver Pin</td><td>Transmitter Pin</td><td>5V</td><td>GND</td></tr>
</table>

<script>

   var purchase_link = 'https://m5stack.com/collections/m5-unit/products/ir-unit';
   anchor_search(purchase_link);
   scrollFunc();

</script>