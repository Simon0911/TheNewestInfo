<template>
  <section class="theNewestInfo" style="width: 1200px; margin: 0 auto">
    <h2>最新消息</h2>
    <el-row :gutter="23">
      <el-col :span="7">
        <div class="grid-content bg-purple">
          <div class="search">
            <input type="text" />
          </div>
          <div class="competitionCategory">
            <h3>競賽分類</h3>
            <ul style="list-style: none">
              <li>聯網未來挑戰賽</li>
              <li>CONNECTIVITY INNOVATION AWARDS</li>
              <li>B5G/6G用戶端與 小基站天線系統設計</li>
              <li>5G領航創新應用競賽</li>
            </ul>
          </div>
          <div class="webCategory">
            <h3>全站分類</h3>
            <ul style="list-style: none">
              <li>最新消息</li>
              <li>熱門消息 Top5</li>
            </ul>
          </div>
        </div>
      </el-col>
      <el-col :span="17">
        <div class="grid-content bg-purple-light">
          <el-card class="box-card" style="margin-bottom: 86px">
            <div class="text item">
              <div class="item-content">
                <h3 style="text-align: left">2020通訊大賽頒獎典禮</h3>
                <span style="text-align: left">2020.12.10</span>
                <p style="text-align: left">
                  不畏新冠肺炎疫情，堅持舉辦並邁入第19年的「Mobileheroes
                  通訊大賽」，再度由經濟部工業局號召產、官、學界與各路參賽好手，在艱難時局下熱情開戰，並於12月15日假中油大樓國光會議廳，盛大進行頒...
                </p>
              </div>
              <el-button type="primary">閱讀全文</el-button>
            </div>
          </el-card>
          <el-card class="box-card" style="margin-bottom: 86px">
            <div class="text item">
              <div class="item-content">
                <h3>2020通訊大賽頒獎典禮</h3>
                <span>2020.12.10</span>
                <p>
                  不畏新冠肺炎疫情，堅持舉辦並邁入第19年的「Mobileheroes
                  通訊大賽」，再度由經濟部工業局號召產、官、學界與各路參賽好手，在艱難時局下熱情開戰，並於12月15日假中油大樓國光會議廳，盛大進行頒...
                </p>
              </div>
              <el-button type="primary">閱讀全文</el-button>
            </div>
          </el-card>
        </div>
      </el-col>
    </el-row>
    <el-pagination background layout="prev, pager, next" :total="1000">
    </el-pagination>
  </section>
</template>

<script>
export default {};
</script>
