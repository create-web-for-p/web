<template>
  <div>
      <div class="container">
          <h1>การใช้ container</h1>
      </div>
      <div class="container" style="background-color: pink;"> 
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet, fuga.</p>
      </div>
       <div class="container-fluid" style="background-color: pink;"> 
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet, fuga.</p>
      </div>
      <hr>
        <div class="container">
          <h1>ขนาดข้อความ</h1>
          <p class="h1" style="background-color: pink;">h1</p>
          <p class="h2" style="background-color: pink;">h2</p>
          <p class="h3" style="background-color: pink;">h3</p>
          <p class="h4" style="background-color: pink;">h4</p>
          <p class="h5" style="background-color: pink;">h5</p>
          <hr>
          <h1>ความหนาข้อความ</h1>
          <p class="fw-bold">bold</p>
          <p class="fw-bolder">bolder</p>
          <p class="fst-italic">italic</p>
          <h1>รูปแบบข้อความ</h1>
          <p class="text-uppercase">hello</p>
          <p class="text-lowercase">HELLO</p>
          <h1>inline</h1>
          <ul class="list-inline">
            <li class="list-inline-item">asd</li>
            <li class="list-inline-item">asd</li>
            <li class="list-inline-item">asd</li>
            <li class="list-inline-item">asd</li>
          </ul>
          <hr>
          <h1>สีและพื้นหลัง</h1>
          <h3>กำหนดสีข้อความ</h3>
          <p class="text-primary">text-primary</p>
          <p class="text-secondary">secondary</p>
          <p class="text-danger">danger</p>
          <p class="text-success">success</p>
          <p class="text-info">info</p>
          <p class="text-warning">warning</p>
          <h3>สีพื้นหลัง</h3>
          <p class="bg-primary">text-primary</p>
          <p class="bg-secondary">secondary</p>
          <p class="bg-danger">danger</p>
          <p class="bg-success">success</p>
          <p class="bg-info">info</p>
          <p class="bg-warning">warning</p>
          <hr>
          <h1>aliment</h1>
          <p class="text-start bg-success d-inline">text-start</p>
          <p class="text-center bg-success">text-center</p>
          <p class="text-end">text-end</p>
          <hr>
          <h1>float and fix position</h1>
          <div class="bg-success clearfix">
              <button class="float-start">float-start</button>
              <button class="float-end">float-end</button>
          </div>
          <h1 class="invisible">invisible</h1>
          <hr>
          <h1>magin ระยะห่างจากด้านรอบๆ</h1>
          <p class="bg-warning mb-0">mb-0</p>
          <p class="bg-warning mb-1">mb-1</p>
          <p class="bg-warning mb-2">mb-2</p>
          <p class="bg-warning mb-3">mb-3</p>
          <p class="bg-warning mb-4">mb-4</p>
          <p class="bg-warning mb-5">mb-5</p>
           <h1 class="mt-5 bg-warning">Margin Top</h1>
        <h1 class="mb-5 bg-warning">Margin Bottom</h1>
        <h1 class="ms-5 bg-warning">Margin Left</h1>
        <h1 class="me-5 bg-warning">Margin Right</h1>

        <!-- ML & MR Spacing -->
        <h1 class="me-5 bg-primary">Margin Right 5</h1>
        <h1 class="ms-3 bg-primary">Margin Left 3</h1>

        <!-- MX -->
        <h1 class="bg-danger mx-3">Margin Left & Right 5</h1>
        <!-- MY -->
        <h1 class="bg-danger my-4">Margin Top & Bottom 5</h1>
        <!-- Blank -->
        <h1 class="bg-warning m-5">Margin Blank</h1>
              <br>
      <br>
      <hr>
      <h1>การกำหนดความกว้างและความสุง</h1>
        <div class="bg-danger w-25">width 25</div>
        <div class="bg-danger w-50">width 50</div>
        <div class="bg-danger w-75">width 75</div>
        <div class="bg-danger w-100">width 100</div>
        <div class="bg-danger w-auto">width auto</div>
        <br>
        <!-- <div style="height: 300px;">
            <div class="bg-primary h-25 my-3">Height 25%</div>
            <div class="bg-primary h-50 my-3">Height 50%</div>
            <div class="bg-primary h-75 my-3">Height 75%</div>
            <div class="bg-primary h-100 my-3">Height 100%</div>
            <div class="bg-primary h-auto my-3">Height Auto</div>
        </div> -->
        <hr>
        <h1>ปุ่ม</h1>
        <button class="btn btn-primary">Primary</button>
        <button class="btn btn-secondary">Secondary</button>
        <button class="btn btn-success">Success</button>
        <button class="btn btn-danger">Danger</button>
        <button class="btn btn-warning">Warning</button>
        <button class="btn btn-info">Info</button>
        <button class="btn btn-light">Light</button>
        <button class="btn btn-dark">Dark</button>
        <br>
        <br>
          <!-- Outline Button -->
        <button class="btn btn-outline-primary">Outline Primary</button>
        <button class="btn btn-outline-secondary">Outline Secondary</button>
        <button class="btn btn-outline-success">Outline Success</button>
        <button class="btn btn-outline-danger">Outline Danger</button>
        <button class="btn btn-outline-warning">Outline Warning</button>
        <button class="btn btn-outline-info">Outline Info</button>
        <button class="btn btn-outline-light">Outline Light</button>
        <button class="btn btn-outline-dark">Outline Dark</button>
        <br><br>
          <div class="btn-group">
            <button class="btn btn-primary">Home</button>
            <button class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Menu</button>
            <div class="dropdown-menu">
                <a href="#" class="dropdown-item">Item 1</a>
                <a href="#" class="dropdown-item">Item 2</a>
                <a href="#" class="dropdown-item">Item 3</a>
            </div>
            <br>
            <hr>
           
        </div>
         <h1>menu bar</h1>
           <nav class="navbar navbar-expand-sm navbar-dark bg-success">
        <!-- Content -->
        <div class="container-fluid">
            <!-- Brand -->
            <a href="#" class="navbar-brand">KongRuksiam</a>
            <!-- Menu -->
            <ul class="navbar-nav">
                <li class="nav-item">
                    <a href="#" class="nav-link">Home</a>
                </li>
                <li class="nav-item">
                    <a href="#" class="nav-link">About</a>
                </li>
            </ul>
        </div>
    </nav>
    <br>
    <!-- Navbar Toggle -->
    <nav class="navbar navbar-expand-sm navbar-dark bg-dark">
        <!-- Content -->
        <div class="container-fluid">
            <!-- Brand -->
            <a href="#" class="navbar-brand">KongRuksiam</a>
            <button class="navbar-toggler" data-bs-toggle="collapse" data-bs-target="#navbarToggle">
                <span class="navbar-toggler-icon"></span>
            </button>
            <!-- Menu -->
            <div class="collapse navbar-collapse" id="navbarToggle">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a href="#" class="nav-link">Home</a>
                    </li>
                    <li class="nav-item">
                        <a href="#" class="nav-link">About</a>
                    </li>
                    <li class="nav-item">
                        <a href="#" class="nav-link">Contact</a>
                    </li>
                    <li class="nav-item">
                        <a href="#" class="nav-link">Product</a>
                    </li>
                </ul>
              
                
            </div>

        </div>
    </nav>
    <hr>
    <h1>การกำหนด list</h1>
     <ul class="list-group">
            <li class="list-group-item">List Regular</li>
            <li class="list-group-item list-group-item-primary">List Primary</li>
            <li class="list-group-item list-group-item-secondary">List Secondary</li>
            <li class="list-group-item list-group-item-success">List Success</li>
            <li class="list-group-item list-group-item-danger">List Danger</li>
            <li class="list-group-item list-group-item-warning">List Warning</li>
            <li class="list-group-item list-group-item-info">List Info</li>
            <li class="list-group-item list-group-item-light">List Light</li>
            <li class="list-group-item list-group-item-dark">List Dark</li>
        </ul>
        <br>
        <h1>breadcrumd</h1>
         <ol class="breadcrumb">
            <li class="breadcrumb-item">สินค้า</li> 
            <li class="breadcrumb-item">เฟอร์นิเจอร์</li>
            <li class="breadcrumb-item active">โซฟา</li>
        </ol>
        <!-- แบบ Link -->
        <ol class="breadcrumb">
            <li class="breadcrumb-item"><a href="#">สินค้า</a></li>
            <li class="breadcrumb-item"><a href="#">เฟอร์นิเจอร์</a></li>
            <li class="breadcrumb-item"><a href="#">โซฟา</a></li>
        </ol>
        <!-- Badge -->
        <ul class="list-group">
            <li class="list-group-item d-flex justify-content-between">สินค้าทั้งหมด<span class="badge bg-success">45</span></li>
            <li class="list-group-item d-flex justify-content-between">เฟอร์นิเจอร์<span class="badge bg-primary">15</span></li>
            <li class="list-group-item d-flex justify-content-between">เครื่องใช้ไฟฟ้า<span class="badge bg-danger">15</span></li>
            <li class="list-group-item d-flex justify-content-between">เครื่องสำอางค์<span class="badge bg-warning">15</span></li>
        </ul>
        <br><br>
        <hr>
        <h1>alert</h1>
          <div class="alert">
            <strong>Simple Alert</strong>
        </div>

        <!-- กำหนดสีของ Alert -->
        <div class="alert alert-primary">
            <strong>Primary</strong>
        </div>
        <div class="alert alert-secondary">
            <strong>Secondary</strong>
        </div>
        <div class="alert alert-success">
            <strong>Success</strong>
        </div>
        <div class="alert alert-danger">
            <strong>Danger</strong>
        </div>
        <div class="alert alert-warning">
            <strong>Warning</strong>
        </div>
        <div class="alert alert-info">
            <strong>Info</strong>
        </div>
        <div class="alert alert-light">
            <strong>Light</strong>
        </div>
        <div class="alert alert-dark">
            <strong>Dark</strong>
        </div>

        <!-- Link Alert -->
        <div class="alert alert-success">
            <strong>Link Alert</strong>
            <a href="#" class="alert-link">Link</a>
        </div>

        <!-- การปิด Alert -->
        <div class="alert alert-success alert-dismissible">
            <button class="btn-close" data-bs-dismiss="alert"></button>
            <h2 class="alert-heading">Hello World</h2>
            <hr>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Praesentium reprehenderit distinctio fuga magni maxime assumenda inventore, laudantium perferendis esse tempora.</p>
        <br><br>
        <hr>
        <div class="progress">
            <div class="progress-bar" style="width: 50%;"></div>
        </div>
        <br>
        <!-- สร้าง Progressbar พร้อม Text -->
        <div class="progress">
            <div class="progress-bar" style="width: 70%;">70%</div>
        </div>
        <br>
        <!-- กำหนดสีให้ Progressbar -->
        <div class="progress">
            <div class="progress-bar bg-success" style="width: 99%;">Success</div>
        </div>
        <br>
        <div class="progress">
            <div class="progress-bar bg-warning" style="width: 99%;">Warning</div>
        </div>
        <br>
        <div class="progress">
            <div class="progress-bar bg-primary" style="width: 99%;">Primary</div>
        </div>
        <br>
        <!-- กำหนดความสูง -->
        <div class="progress" style="height: 50px;">
            <div class="progress-bar bg-danger" style="width: 75%;">75%</div>
        </div>
        <br>
        <!-- Striped Progressbar -->
        <div class="progress" style="height: 50px;">
            <div class="progress-bar bg-success progress-bar-striped" style="width: 90%;">90%</div>
        </div>
        <br>
        <!-- กำหนด Striped Animation -->
        <div class="progress" style="height: 50px;">
            <div class="progress-bar bg-primary progress-bar-striped progress-bar-animated" style="width: 90%;">90%</div>
        </div>
        <br>
        <!-- Multiple Progressbar -->
        <div class="progress" style="height: 50px;">
            <div class="progress-bar bg-warning" style="width: 25%;"></div>
            <div class="progress-bar bg-success" style="width: 25%;"></div>
            <div class="progress-bar bg-primary" style="width: 50%;"></div>
        </div>
        </div>
        </div>
        
  </div>
</template>
<script>

export default {
  
}
</script>

