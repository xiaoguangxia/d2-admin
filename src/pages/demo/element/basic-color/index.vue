<template>
  <d2-container type="ghost">
    
    <el-card shadow="never" class="d2-mb">
      <template slot="header">主色</template>
      <el-row :gutter="20">
        <el-col :span="6">
          <div class="color color-primary">
            <d2-element-basic-color-info name="Blue" sass="$color-primary" color="#409EFF"/>
          </div>
        </el-col>
      </el-row>
    </el-card>
    
    <el-card shadow="never" class="d2-mb">
      <template slot="header">辅助色</template>
      <el-row :gutter="20">
        <el-col :span="6">
          <div class="color color-info">
            <d2-element-basic-color-info name="Blue" sass="$color-primary" color="#409EFF"/>
          </div>
        </el-col>
        <el-col :span="6">
          <div class="color color-success">
            <d2-element-basic-color-info name="Blue" sass="$color-primary" color="#409EFF"/>
          </div>
        </el-col>
        <el-col :span="6">
          <div class="color color-warning">
            <d2-element-basic-color-info name="Blue" sass="$color-primary" color="#409EFF"/>
          </div>
        </el-col>
        <el-col :span="6">
          <div class="color color-danger">
            <d2-element-basic-color-info name="Blue" sass="$color-primary" color="#409EFF"/>
          </div>
        </el-col>
      </el-row>
    </el-card>
    
    <el-card shadow="never">
      <template slot="header">中性色</template>
      <el-row :gutter="20" class="d2-mb">
        <el-col :span="6">
          <div class="color color-text-main">
            <d2-element-basic-color-info name="Blue" sass="$color-primary" color="#409EFF"/>
          </div>
        </el-col>
        <el-col :span="6">
          <div class="color color-text-normal">
            <d2-element-basic-color-info name="Blue" sass="$color-primary" color="#409EFF"/>
          </div>
        </el-col>
        <el-col :span="6">
          <div class="color color-text-sub">
            <d2-element-basic-color-info name="Blue" sass="$color-primary" color="#409EFF"/>
          </div>
        </el-col>
        <el-col :span="6">
          <div class="color color-text-placehoder">
            <d2-element-basic-color-info name="Blue" sass="$color-primary" color="#409EFF"/>
          </div>
        </el-col>
      </el-row>
      <el-row :gutter="20">
        <el-col :span="6">
          <div class="color color-border-1">
            <d2-element-basic-color-info theme="dark" name="Blue" sass="$color-primary" color="#409EFF"/>
          </div>
        </el-col>
        <el-col :span="6">
          <div class="color color-border-2">
            <d2-element-basic-color-info theme="dark" name="Blue" sass="$color-primary" color="#409EFF"/>
          </div>
        </el-col>
        <el-col :span="6">
          <div class="color color-border-3">
            <d2-element-basic-color-info theme="dark" name="Blue" sass="$color-primary" color="#409EFF"/>
          </div>
        </el-col>
        <el-col :span="6">
          <div class="color color-border-4">
            <d2-element-basic-color-info theme="dark" name="Blue" sass="$color-primary" color="#409EFF"/>
          </div>
        </el-col>
      </el-row>
    </el-card>
    
  </d2-container>
</template>

<script>
export default {
  components: {
    'd2-element-basic-color-info': () => import('./components/info.vue')
  }
}
</script>


<style lang="scss" scoped>
@import '~@/assets/style/unit/_color.scss';
.color {
  border-radius: 4px;
  height: 90px;
}

.color-primary {
  background-color: $color-primary;
}

.color-info {
  background-color: $color-info;
}
.color-success {
  background-color: $color-success;
}
.color-warning {
  background-color: $color-warning;
}
.color-danger {
  background-color: $color-danger;
}

.color-text-main {
  background-color: $color-text-main;
}
.color-text-normal {
  background-color: $color-text-normal;
}
.color-text-sub {
  background-color: $color-text-sub;
}
.color-text-placehoder {
  background-color: $color-text-placehoder;
}

.color-border-1 {
  background-color: $color-border-1;
}
.color-border-2 {
  background-color: $color-border-2;
}
.color-border-3 {
  background-color: $color-border-3;
}
.color-border-4 {
  background-color: $color-border-4;
}
</style>

