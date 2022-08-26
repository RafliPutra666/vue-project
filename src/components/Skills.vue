<template> 
  <WelcomeItem> 
    <template #icon> 
      <DocumentationIcon /> 
    </template> 
    <div class="div"> 
      <div class="flex"> 
        <h3>HTML</h3> 
        <h3>80%</h3> 
      </div> 
      <img alt="" class="logo" src="@/assets/Blue_K_letter__Keystone_JS_Logo__icons_logos_emojis__tech_companies_png___Klipartz-removebg-preview.png" width="35" height="35" />
      <div class="skills_bar"> 
        <span class="skills_percetage skills_html"></span> 
      </div> 
    </div>   
  </WelcomeItem> 
 
  <WelcomeItem> 
    <template #icon> 
      <ToolingIcon /> 
    </template> 
    <div class="div"> 
      <div class="flex"> 
        <h3>CSS</h3> 
        <h3>75%</h3> 
      </div> 
            <img alt="" class="logo" src="@/assets/CSS3_Logo_Vector_SVG__PNG_Free_Download_-_Logowik_com-removebg-preview.png" width="35" height="35" />

      <div class="skills_bar"> 
        <span class="skills_percetage skills_css"></span> 
      </div> 
    </div>   
  </WelcomeItem> 
 
  <WelcomeItem> 
    <template #icon> 
      <EcosystemIcon /> 
    </template> 
    <div class="div"> 
      <div class="flex"> 
        <h3>FIGMA</h3> 
        <h3>80%</h3> 
      </div> 
        <img alt="" class="logo" src="@/assets/Figma_Logo___Real_Company___Alphabet__Letter_F_Logo-removebg-preview.png" width="35" height="35" />

      <div class="skills_bar"> 
        <span class="skills_percetage skills_figma"></span> 
      </div> 
    </div>    
  </WelcomeItem> 
 
  <WelcomeItem> 
    <template #icon> 
      <CommunityIcon /> 
    </template> 
    <div class="div"> 
      <div class="flex"> 
        <h3>JAVA SCRIPT</h3> 
        <h3>50%</h3> 
      </div> 
        <img alt="" class="logo" src="@/assets/JavaScript Logo.png" width="35" height="35" />
      <div class="skills_bar"> 
        <span class="skills_percetage skills_js"></span> 
      </div> 
    </div>   
  </WelcomeItem> 


  <WelcomeItem> 
    <template #icon> 
      <DocumentationIcon /> 
    </template> 
    <div class="div"> 
      <div class="flex"> 
        <h3>BOOTSTRAP</h3> 
        <h3>50%</h3> 
      </div> 
        <img alt="" class="logo" src="@/assets/Bootstrap.png" width="35" height="35" />
      <div class="skills_bar"> 
        <span class="skills_percetage skills_bootstrap"></span> 
      </div> 
    </div>   
  </WelcomeItem> 

  
 
  <!-- <WelcomeItem> 
    <template #icon> 
      <SupportIcon /> 
    </template> 
    <template #heading>Support Vue</template> 
 
    As an independent project, Vue relies on community backing for its sustainability. You can help 
    us by 
    <a target="_blank" href="https://vuejs.org/sponsor/">becoming a sponsor</a>. 
  </WelcomeItem> --> 
</template> 
 
<style> 
.div{ 
  height: 90px; 
} 
 
.flex{ 
  display: flex; 
  justify-content: space-between; 
} 
 
h3{ 
  font-size: 1.2rem; 
  font-weight: 500; 
  margin-bottom: 0.4rem; 
  color: var(--color-heading); 
} 
 
.skills_bar, 
.skills_percetage{ 
  margin-top: 5px; 
  height: 5px; 
  border-radius: .25rem; 
} 
 
.skills_bar{ 
  background-color: #fff; 
} 
 
.skills_percetage{ 
  display: block; 
  background-color: hsla(160, 100%, 37%, 1); 
} 
 
.skills_html{ 
  width: 80%; 
} 
.skills_css{ 
  width: 75%; 
} 
.skills_figma{ 
  width: 80%; 
} 
 
.skills_js{ 
  width: 50%; 
} 

.skills_bootstrap{
  width: 50%;
}
</style>