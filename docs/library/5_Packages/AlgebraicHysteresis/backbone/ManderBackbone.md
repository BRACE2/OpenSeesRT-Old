# Mander

This file contains the implementation of 
ManderBackbone, which the concrete backbone function given
by Mander, Priestly, and Park (1988)

:::{apidoc="opensees.backbone.Mander"}
:::

Code developed by: <span style="color:blue">MHS</span>
Created: Mar 2001

```cpp
class ManderBackbone : public HystereticBackbone
{
 public:
  ManderBackbone(int tag, double fc, double epsc, double Ec);

 private:
  double fpc;
  double epsc;
  double Ec;
};
```