<template>
<div id="review">

  <v-container>
 <div class="button-profile">
   
    <v-btn block color="secondary" dark large to="/HelloWorld">Profile</v-btn>  
    
  </div>

  <v-carousel style="margin: 20dp;">
    <v-carousel-item
      v-for="(item,i) in items"
      :key="i"
      :src="item.src"
    ></v-carousel-item>
   </v-carousel>

    <h1  class="text-xs-center" >คลังข้อมูลแมว</h1>        
    <h1> {{ msg }} </h1>
    
<div id="app">
  <v-app id="inspire">
    <div class="card">
    <v-layout>
      <v-flex >
        <v-card>
          <v-img
            src="https://108dog.com/market/board/SubAttachments/1510899175-146-8.jpg"
            aspect-ratio="2.50"
          ></v-img>
  
          <v-card-title primary-title>
            <div>
              <h3 class="headline mb-2">แมววิเชียรมาศ</h3>
              <div>
                <p>
                    แมววิเชียรมาศ ตรงกับความหมายว่า "เพชรแห่งดวงจันทร์" หรือ "Moon Diamond" บางตำราก็เรียก "แมวแก้ว" ซึ่งก็ตรงกับคำว่า "วิเชียร" 
                แมวชนิดนี้มักถูกเข้าใจผิดว่าเป็นแมวเก้าแต้มเสมอ ที่จริงแล้วไม่ถูกต้อง แมวเก้าแต้มคือแมวที่มีสีพื้นสีขาว และมีแต้มบนร่างกาย 9 แห่ง 
                เหตุที่มักเข้าใจผิดเพราะแมววิเชียรมาศ จะมีสีพื้นสีขาวงาช้าง (หรือโบราณจะเป็นขาวล้วนก็ไม่ทราบ) และมีแต้มที่จมูกครอบไปถึงปากเป็นหนึ่งแห่ง 
                กับขาทั้งสี่ หูสอง หางหนึ่ง และที่อวัยวะเพศอีกหนึ่ง รวมเป็น 9 แห่งเช่นกัน ในแมววิเชียรมาศนี้แต้มตามตำราว่าไว้ว่าต้องเป็นสีดำดังหมึกวาด 
                แต่ปัจจุบันเมื่อดูให้ดีแล้วจะเป็นแต้มสีน้ำตาลเข้มเกือบดำ ไม่ได้ดำสนิท หรือที่ต่างประเทศเรียกว่า Seal brown หรือแต้มสีครั่ง 
                แมววิเชียรมาศเป็นที่รู้จักในต่างประเทศโดยใช้ชื่อว่า แมวสยาม (Siamese Cat) แต่ต่างประเทศจะมีแต้มสีอื่นที่หลากหลายกว่า 
                ซึ่งประเทศไทยจะยอมรับเฉพาะแมวที่มีแต้มสีน้ำตาลเข้มเท่านั้น นัยน์ตาสีฟ้าก็เป็นเสน่ห์อีกอย่างหนึ่งของแมวชนิดนี้
                </p>
              </div>
            </div>
          </v-card-title>
  
          <v-card-actions>
            
          </v-card-actions>
        </v-card>
      </v-flex>
    </v-layout>
</div>

 <div class="card">
    <v-layout>
      <v-flex >
        <v-card>
          <v-img
            src="http://breedinfo.ru/uploads/posts/2016-01/2_bengal_cat.jpg"
            aspect-ratio="2.50"
          ></v-img>
  
          <v-card-title primary-title>
            <div>
              <h3 class="headline mb-2">แมวเบงกอล (Bengal)</h3>
              <div>
                 <p>
                     การกำเนิดขึ้นของแมวเบงกอล เริ่มโดย คุณ Jean Mills หญิงชาวมลรัฐแอริโซนา ประเทศสหรัฐอเมริกา ที่หลงใหลในลวดลายของแมวป่า เธอใช้เวลาถึง 20 ปี (เริ่มมาตั้งแต่ปี ค.ศ. 1980 หรือ พ.ศ. 2523) ในการพัฒนาให้มีจุด (Spotted ที่ใหญ่และแมวตัวผู้ไม่เป็นหมัน (แมวตัวผู้จะเป็นหมันใน F1 and F2) จนสามารถสร้างจุดให้ใหญ่และมีสีที่ตัดกันในจุดมากขึ้นด้วย และเธอตั้งชื่อสายพันธุ์นี้ว่า เบงกอล ตามชื่อวิทยาศาสตร์ของแมวป่าที่เรียกกันว่า Felis Bengalensis นั่นเอง
                 </p>
              </div>
            </div>
          </v-card-title>
  
          <v-card-actions>
            
          </v-card-actions>
        </v-card>
      </v-flex>
    </v-layout>
</div>


 <div class="card">
    <v-layout>
      <v-flex >
        <v-card>
          <v-img
            src="https://kuppaa.files.wordpress.com/2014/01/white-persian-cat-high-definitionwhite-persian-cat-funny-cat-wallpapers-pictures-images-and-photos-2rl61soh.jpg"
            aspect-ratio="2.50"
          ></v-img>
  
          <v-card-title primary-title>
            <div>
              <h3 class="headline mb-2"> แมวเปอร์เซีย Persian</h3>
              <div>
                 <p>
                  แมวเปอร์เซีย เป็นพันธุ์เก่าแก่มีถิ่น กำเนิดในแถบเปอร์เซียหรืออิหร่าน ถูกนำไปเลี้ยงในยุโรป และอเมริกากว่า 100 ปีแล้ว แมวเปอร์เซียมีขนยาวนุ่ม ลำตัวป้อม หน้ากลม ตากลมจมูกสั้นมากจนแบนสีสันหลากหลายมาก นิสัยอ่อนโยน ร่าเริง ซุกซนแต่พองามแระจบประแจงเป็นที่นิยมกันมากในหมู่คนเลี้ยงแมวแม้ว่าราคายัง สูงอยู่ก็ตาม
                 </p>
              </div>
            </div>
          </v-card-title>
  
          <v-card-actions>
            
          </v-card-actions>
        </v-card>
      </v-flex>
    </v-layout>
</div>


 <div class="card">
    <v-layout>
      <v-flex >
        <v-card>
          <v-img
            src="https://f.ptcdn.info/470/021/000/1405936186-ScottishFo-o.jpg"
            aspect-ratio="2.50"
          ></v-img>
  
          <v-card-title primary-title>
            <div>
              <h3 class="headline mb-2">แมวสก๊อตติสโฟลด์ Scottish fold</h3>
              <div>
                 <p>
                    มีถิ่นกำเนิดใน สก็อตแลนด์ในปี ค.ศ. 1961 พบครั้งเมื่อเกษตรกรชาวสก็อตแลนด์ได้ให้กำเนิดลูกแมวผิดปรกติ โดยมีหูหลุบลงไป ซึ่งปรกติแมวทั่วไปหูจะตั้งขึ้น และเมื่อนำมาผสมข้ามพันธุ์จนได้พันธุ์ที่แน่นอนออกมา แมวสก็อตติชโฟลด์เป็นแมวขนาดกลางขนแน่นแต่ค่อนข้างยาวกว่าแมวขนสั้นทั่วไป มีหลากสีดวงตากลมโตมีลักษณะเด่นคือหูหลุบ มีทั้งขนสั้นและขนยาว
                 </p>
              </div>
            </div>
          </v-card-title>
  
          <v-card-actions>
            
          </v-card-actions>
        </v-card>
      </v-flex>
    </v-layout>
</div>


  </v-app>
</div>


  </v-container>
  </div>
</template>

<script>
  export default {
    name: 'review',
    data () {
      return {
        items: [
          {
            src: 'https://images.wallpaperscraft.com/image/cat_british_eye_26816_1920x1080.jpg'
          },
          {
            src: 'https://images.wallpaperscraft.com/image/cat_surprise_look_striped_96597_1920x1080.jpg'
          },
          {
            src: 'http://pixcorners.com/wp-content/uploads/2017/01/Blue-Eyes-Cat-Ultra-HD-Wallpaper-1920x1080.jpg'
          },
          {
            src: 'https://hdqwalls.com/download/cute-white-cat-1920x1080.jpg'
          }
        ],
        employee_id: null,
        name: null,
        dept: null,
        position: null
      }
    }
  }
</script>

<style scoped>

h1, h2 {
  font-weight: normal;
  margin: 2em;
}

.button-profile{
  
 margin-bottom: 2em

}

.card{
  margin: 2em;
}

</style>