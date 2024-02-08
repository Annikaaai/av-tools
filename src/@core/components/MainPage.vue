<script setup lang='ts'>

const avMessageItems = [
  'Автоответчики',
  'Статистика по объявлениям и сообщениям',
  'Оповещения о сообщениях в Telegram',
  'Мультиаккаунты',
]
const avPriceItems = [
  'Актуальная информация',
  'Поиск по регионам и городам',
  'Поиск по категориям',
  'Высокая скорость работы',
]
const avWordStatItems = [
  'Актуальная информация',
  'Поиск по регионам и городам',
  'Поиск по категориям',
  'Высокая скорость работы',
]
const News = [
  {
    data: '23.01.2023',
    version: 'v3.2',
    new_information: 'В раздел создания автоответчиков на все сообщения добавлена кнопка быстрой вставки тега, разделяющего автоответ на несколько сообщений.',
    fixed_1: 'Исправлена недоработка, из-за которой при настройке автоответчика на ключевые слова для всего аккаунта Авито не отображалась кнопка предварительного просмотра для первой группы кейвордов.',
    fixed_2: 'Исправлена некорректная работа «шаблонных ответов» Telegram для объявлений.'
  }
]
</script>
<template>
  <v-container class = "top-card d-flex align-center justify-center justify-md-start mt-13 rounded-lg">
        <svg width="33" height="33" viewBox="0 0 33 33" fill="none" xmlns="http://www.w3.org/2000/svg">
                <rect width="33" height="33" fill="#F5F5F5"/>
                <rect width="2170" height="1078" transform="translate(-517 -77)" fill="#F7F7F7"/>
                <rect x="-21.5" y="-23.5" width="1630" height="80" rx="5.5" fill="#EFE6FB" fill-opacity="0.48"/>
                <rect x="-21.5" y="-23.5" width="1630" height="80" rx="5.5" stroke="#D8E2EF"/>
                <path d="M32.5104 28.2753H0.489643C0.219164 28.2753 0 28.4945 0 28.7649V30.2338C0 30.5042 0.219164 30.7235 0.489643 30.7235H32.5104C32.7808 30.7235 33 30.5042 33 30.2338V28.7649C33 28.4945 32.7808 28.2753 32.5104 28.2753Z" fill="url(#paint0_linear_0_1)"/>
                <path d="M0.638081 26.0229H2.10701C2.37749 26.0229 2.59665 25.8036 2.59665 25.5333V14.5169C2.59665 14.2465 2.37749 14.0272 2.10701 14.0272H0.638081C0.367602 14.0272 0.148438 14.2465 0.148438 14.5169V25.5333C0.148437 25.8037 0.367602 26.0229 0.638081 26.0229Z" fill="url(#paint1_linear_0_1)"/>
                <path d="M5.68105 26.0236H7.14998C7.42046 26.0236 7.63962 25.8044 7.63962 25.534V8.64186C7.63962 8.37148 7.42046 8.15222 7.14998 8.15222H5.68105C5.41057 8.15222 5.19141 8.37148 5.19141 8.64186V25.534C5.19141 25.8045 5.41057 26.0236 5.68105 26.0236Z" fill="url(#paint2_linear_0_1)"/>
                <path d="M10.724 26.0233H12.1929C12.4634 26.0233 12.6826 25.804 12.6826 25.5336V11.5794C12.6826 11.309 12.4634 11.0897 12.1929 11.0897H10.724C10.4535 11.0897 10.2344 11.309 10.2344 11.5794V25.5336C10.2344 25.8041 10.4535 26.0233 10.724 26.0233Z" fill="url(#paint3_linear_0_1)"/>
                <path d="M15.767 26.0234H17.2359C17.5064 26.0234 17.7256 25.8041 17.7256 25.5337V2.76589C17.7256 2.49551 17.5064 2.27625 17.2359 2.27625H15.767C15.4965 2.27625 15.2773 2.49551 15.2773 2.76589V25.5337C15.2773 25.8042 15.4966 26.0234 15.767 26.0234Z" fill="url(#paint4_linear_0_1)"/>
                <path d="M20.808 26.0229H22.2769C22.5474 26.0229 22.7666 25.8037 22.7666 25.5333V10.9915C22.7666 10.7211 22.5474 10.5018 22.2769 10.5018H20.808C20.5375 10.5018 20.3184 10.7211 20.3184 10.9915V25.5333C20.3184 25.8038 20.5376 26.0229 20.808 26.0229Z" fill="url(#paint5_linear_0_1)"/>
                <path d="M25.851 26.0236H27.3199C27.5904 26.0236 27.8095 25.8044 27.8095 25.534V8.64186C27.8095 8.37148 27.5904 8.15222 27.3199 8.15222H25.851C25.5805 8.15222 25.3613 8.37148 25.3613 8.64186V25.534C25.3613 25.8045 25.5806 26.0236 25.851 26.0236Z" fill="url(#paint6_linear_0_1)"/>
                <path d="M30.8939 26.0232H32.3629C32.6333 26.0232 32.8525 25.804 32.8525 25.5336V13.3421C32.8525 13.0717 32.6333 12.8524 32.3629 12.8524H30.8939C30.6235 12.8524 30.4043 13.0717 30.4043 13.3421V25.5336C30.4043 25.8041 30.6235 26.0232 30.8939 26.0232Z" fill="url(#paint7_linear_0_1)"/>
                <defs>
                <linearGradient id="paint0_linear_0_1" x1="16.5" y1="28.2753" x2="16.5" y2="30.7235" gradientUnits="userSpaceOnUse">
                <stop stop-color="#AE83FD"/>
                <stop offset="1" stop-color="#9155FD"/>
                </linearGradient>
                <linearGradient id="paint1_linear_0_1" x1="1.37255" y1="14.0272" x2="1.37255" y2="26.0229" gradientUnits="userSpaceOnUse">
                <stop stop-color="#AE83FD"/>
                <stop offset="1" stop-color="#9155FD"/>
                </linearGradient>
                <linearGradient id="paint2_linear_0_1" x1="6.41551" y1="8.15222" x2="6.41551" y2="26.0236" gradientUnits="userSpaceOnUse">
                <stop stop-color="#AE83FD"/>
                <stop offset="1" stop-color="#9155FD"/>
                </linearGradient>
                <linearGradient id="paint3_linear_0_1" x1="11.4585" y1="11.0897" x2="11.4585" y2="26.0233" gradientUnits="userSpaceOnUse">
                <stop stop-color="#AE83FD"/>
                <stop offset="1" stop-color="#9155FD"/>
                </linearGradient>
                <linearGradient id="paint4_linear_0_1" x1="16.5015" y1="2.27625" x2="16.5015" y2="26.0234" gradientUnits="userSpaceOnUse">
                <stop stop-color="#AE83FD"/>
                <stop offset="1" stop-color="#9155FD"/>
                </linearGradient>
                <linearGradient id="paint5_linear_0_1" x1="21.5425" y1="10.5018" x2="21.5425" y2="26.0229" gradientUnits="userSpaceOnUse">
                <stop stop-color="#AE83FD"/>
                <stop offset="1" stop-color="#9155FD"/>
                </linearGradient>
                <linearGradient id="paint6_linear_0_1" x1="26.5854" y1="8.15222" x2="26.5854" y2="26.0236" gradientUnits="userSpaceOnUse">
                <stop stop-color="#AE83FD"/>
                <stop offset="1" stop-color="#9155FD"/>
                </linearGradient>
                <linearGradient id="paint7_linear_0_1" x1="31.6284" y1="12.8524" x2="31.6284" y2="26.0232" gradientUnits="userSpaceOnUse">
                <stop stop-color="#AE83FD"/>
                <stop offset="1" stop-color="#9155FD"/>
                </linearGradient>
                </defs>
        </svg>
        <h1 class = "top-card__h1 ml-2 d-none d-md-flex">AV-Tools</h1>
        <p class="top-card__text mt-0 mr-0 mb-0 ml-md-16 ml-2">Автоматизация авито №1</p>
  </v-container>





    <VContainer>
  <VRow >
    <VCol 
      cols="12"
      md="4"
    > 
      <VCard class = "rounded-xl"
        to="av-message/stats"
      >
      <VCardTitle class = "mt-4">
        <div class = "d-flex justify-start">
            <svg width="33" height="33" viewBox="0 0 33 33" fill="none" xmlns="http://www.w3.org/2000/svg">
            <rect width="32.9079" height="32.9079" rx="5" fill="#EFE5FF"/>
            <path d="M24.445 5H8.555C6.04041 5.00277 4.00267 7.11505 4 9.72162V26.8195C4 27.2446 4.22063 27.637 4.57783 27.8468C4.93458 28.0562 5.37273 28.0506 5.72458 27.8321L11.6612 24.1405H24.445C26.9596 24.1378 28.9973 22.0255 29 19.4189V9.72162C28.9973 7.11505 26.9596 5.00277 24.445 5ZM26.7225 19.4189C26.7212 20.7224 25.7021 21.7783 24.445 21.7797H11.3458C11.1394 21.7797 10.937 21.8378 10.76 21.948L6.2775 24.7349V9.72162C6.27883 8.41856 7.29793 7.36219 8.555 7.36081H24.445C25.7021 7.36219 26.7212 8.41856 26.7225 9.72162V19.4189Z" fill="#9155FD"/>
        </svg>
        <div class = "avito-card__title-text ml-2">AV-Message</div>
        </div>
        
      </VCardTitle>
        <VCardText class = "avito-card__text pb-0 pt-2">Инструмент, позволяющий автоматизировать коммуникацию с клиентами и увеличить продажи.</VCardText>
        <VCardText>
          <VList 
            density="compact"
            
            v-for="i, x in avMessageItems"
            :key="x"
            >
                <VListItem class = "list-items">
                        <svg width="14" height="14" viewBox="0 0 14 14" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <circle cx="7" cy="7" r="7" fill="#9155FD" fill-opacity="0.16"/>
                            <path d="M10.8881 6.99924C10.8881 9.14701 9.14701 10.8881 6.99924 10.8881C4.85147 10.8881 3.11035 9.14701 3.11035 6.99924C3.11035 4.85147 4.85147 3.11035 6.99924 3.11035C9.14701 3.11035 10.8881 4.85147 10.8881 6.99924Z" fill="#9155FD" fill-opacity="0.66"/>
                        </svg>
                        {{ i }}
                    
                </VListItem>
            </VList>
        </VCardText>
        <VBtn
          block
          class="rounded-t-0 text_wrap__btn pa-8 d-flex justify-center align-center"
          href="https://t.me/AVMessage_bot"
        >
        <svg width="25" height="23" viewBox="0 0 25 23" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M20.1258 22.3619C19.9305 22.3619 19.7365 22.3041 19.5701 22.1913L13.2841 17.9274L9.91268 20.3533C9.64826 20.5434 9.30744 20.5913 9.00041 20.4815C8.69377 20.3715 8.46088 20.1175 8.37776 19.8026L6.6849 13.3871L0.636131 11.0742C0.255337 10.9286 0.00279388 10.5643 2.30254e-05 10.1566C-0.00274783 9.74886 0.244782 9.38113 0.623728 9.23031L23.6234 0.0785903C23.7277 0.0342567 23.8382 0.00865922 23.9495 0.00179807C23.9894 -0.000576944 24.0294 -0.000576872 24.0691 0.0016662C24.2997 0.0153885 24.5263 0.109334 24.7031 0.28271C24.7214 0.300654 24.7388 0.318995 24.7553 0.338127C24.9018 0.505433 24.9823 0.70942 24.9975 0.917234C25.0011 0.969485 25.0009 1.02239 24.9963 1.0753C24.9931 1.11304 24.9877 1.15065 24.98 1.18799L21.0978 21.5576C21.0354 21.8848 20.8127 22.1587 20.505 22.2863C20.3829 22.337 20.254 22.3619 20.1258 22.3619ZM13.8361 15.9102L19.4354 19.7082L22.4562 3.85843L11.546 14.3568L13.8097 15.8924C13.8188 15.898 13.8275 15.9041 13.8361 15.9102ZM9.17484 15.0656L9.92455 17.9064L11.5398 16.7441L9.42474 15.3093C9.32644 15.2428 9.24226 15.1599 9.17484 15.0656ZM3.71244 10.1314L7.86581 11.7193C8.16335 11.8331 8.38792 12.0832 8.46919 12.3912L8.99592 14.3874C9.02007 14.1571 9.12444 13.9405 9.29399 13.7773L19.6898 3.77398L3.71244 10.1314Z" fill="white"/>
        </svg>

        <div class = "ml-2">Подключить <br class = "card-br"/> тариф</div>
        </VBtn>
      </VCard>
    </VCol>
    <VCol
      cols="12"
      md="4"
    >
      <VCard class = "rounded-xl"
        to="av-price"
      >
      <VCardTitle class = "mt-4">
        <div class = "d-flex justify-start">
            <svg width="33" height="33" viewBox="0 0 33 33" fill="none" xmlns="http://www.w3.org/2000/svg">
                <rect width="32.9079" height="32.9079" rx="5" fill="#EFE5FF"/>
                <path d="M8.5 21.625L4.75 25.3V14.75H8.5M14.75 19.325L12.7875 17.65L11 19.3V9.75H14.75M21 17.25L17.25 21V4.75H21M24.5125 17.0125L22.25 14.75H28.5V21L26.2625 18.7625L17.25 27.7L12.9125 23.925L8.1875 28.5H4.75L12.8375 20.575L17.25 24.3" fill="#9155FD"/>
            </svg>

        <div class = "avito-card__title-text ml-2">AV-Price</div>
        </div>
        
      </VCardTitle>
        <VCardText class = "avito-card__text pb-0 pt-2">Инструмент, позволяющий отслеживать цену за клик при тарифе CPC.</VCardText>
        <VCardText>
            <VList 
            density="compact"
            
            v-for="i, x in avPriceItems"
            :key="x"
            >
                <VListItem class = "list-items">
                        <svg width="14" height="14" viewBox="0 0 14 14" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <circle cx="7" cy="7" r="7" fill="#9155FD" fill-opacity="0.16"/>
                            <path d="M10.8881 6.99924C10.8881 9.14701 9.14701 10.8881 6.99924 10.8881C4.85147 10.8881 3.11035 9.14701 3.11035 6.99924C3.11035 4.85147 4.85147 3.11035 6.99924 3.11035C9.14701 3.11035 10.8881 4.85147 10.8881 6.99924Z" fill="#9155FD" fill-opacity="0.66"/>
                        </svg>
                        {{ i }}
                    
                </VListItem>
            </VList>
        </VCardText>
        <VBtn
          block
          class="rounded-t-0 text_wrap__btn pa-8 d-flex justify-center align-center"
          href="https://t.me/AVMessage_bot"
        >
        <svg width="25" height="23" viewBox="0 0 25 23" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M20.1258 22.3619C19.9305 22.3619 19.7365 22.3041 19.5701 22.1913L13.2841 17.9274L9.91268 20.3533C9.64826 20.5434 9.30744 20.5913 9.00041 20.4815C8.69377 20.3715 8.46088 20.1175 8.37776 19.8026L6.6849 13.3871L0.636131 11.0742C0.255337 10.9286 0.00279388 10.5643 2.30254e-05 10.1566C-0.00274783 9.74886 0.244782 9.38113 0.623728 9.23031L23.6234 0.0785903C23.7277 0.0342567 23.8382 0.00865922 23.9495 0.00179807C23.9894 -0.000576944 24.0294 -0.000576872 24.0691 0.0016662C24.2997 0.0153885 24.5263 0.109334 24.7031 0.28271C24.7214 0.300654 24.7388 0.318995 24.7553 0.338127C24.9018 0.505433 24.9823 0.70942 24.9975 0.917234C25.0011 0.969485 25.0009 1.02239 24.9963 1.0753C24.9931 1.11304 24.9877 1.15065 24.98 1.18799L21.0978 21.5576C21.0354 21.8848 20.8127 22.1587 20.505 22.2863C20.3829 22.337 20.254 22.3619 20.1258 22.3619ZM13.8361 15.9102L19.4354 19.7082L22.4562 3.85843L11.546 14.3568L13.8097 15.8924C13.8188 15.898 13.8275 15.9041 13.8361 15.9102ZM9.17484 15.0656L9.92455 17.9064L11.5398 16.7441L9.42474 15.3093C9.32644 15.2428 9.24226 15.1599 9.17484 15.0656ZM3.71244 10.1314L7.86581 11.7193C8.16335 11.8331 8.38792 12.0832 8.46919 12.3912L8.99592 14.3874C9.02007 14.1571 9.12444 13.9405 9.29399 13.7773L19.6898 3.77398L3.71244 10.1314Z" fill="white"/>
        </svg>

        <div class = "ml-2">Подключить <br class = "card-br"/> тариф +100 р.мес</div>
        </VBtn>
      </VCard>
    </VCol>
    <VCol
      cols="12"
      md="4"
    >
      <VCard class = "rounded-xl"
        to="av-wordstat"
      >
      <VCardTitle class = "mt-4">
        <div class = "d-flex justify-start">
            <svg width="33" height="33" viewBox="0 0 33 33" fill="none" xmlns="http://www.w3.org/2000/svg">
                <rect width="32.9079" height="32.9079" rx="5" fill="#EFE5FF"/>
                <path d="M21 16.6275L25.77 8.38125L27.7162 9.50625L21.8325 19.6875L14.5087 15.4688L9.1425 24.75H27.75V27H5.25V6.75H7.5V23.1075L13.6875 12.375L21 16.6275Z" fill="#9155FD"/>
            </svg>

        <div class = "avito-card__title-text ml-2">AV-Wordstat</div>
        </div>
        
      </VCardTitle>
        <VCardText class = "avito-card__text pb-0 pt-2">Инструмент, позволяющий отслеживать количество поисковых запросов по категориям.</VCardText>
        <VCardText>
            <VList 
            density="compact"
            
            v-for="i, x in avMessageItems"
            :key="x"
            >
                <VListItem class = "list-items m-0">
                        <svg width="14" height="14" viewBox="0 0 14 14" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <circle cx="7" cy="7" r="7" fill="#9155FD" fill-opacity="0.16"/>
                            <path d="M10.8881 6.99924C10.8881 9.14701 9.14701 10.8881 6.99924 10.8881C4.85147 10.8881 3.11035 9.14701 3.11035 6.99924C3.11035 4.85147 4.85147 3.11035 6.99924 3.11035C9.14701 3.11035 10.8881 4.85147 10.8881 6.99924Z" fill="#9155FD" fill-opacity="0.66"/>
                        </svg>
                        {{ i }}
                    
                </VListItem>
            </VList>
        </VCardText>
        <VBtn
          block
          class="rounded-t-0 text_wrap__btn pa-8 d-flex justify-center align-center"
          href="https://t.me/AVMessage_bot"
        >
        <svg width="25" height="23" viewBox="0 0 25 23" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M20.1258 22.3619C19.9305 22.3619 19.7365 22.3041 19.5701 22.1913L13.2841 17.9274L9.91268 20.3533C9.64826 20.5434 9.30744 20.5913 9.00041 20.4815C8.69377 20.3715 8.46088 20.1175 8.37776 19.8026L6.6849 13.3871L0.636131 11.0742C0.255337 10.9286 0.00279388 10.5643 2.30254e-05 10.1566C-0.00274783 9.74886 0.244782 9.38113 0.623728 9.23031L23.6234 0.0785903C23.7277 0.0342567 23.8382 0.00865922 23.9495 0.00179807C23.9894 -0.000576944 24.0294 -0.000576872 24.0691 0.0016662C24.2997 0.0153885 24.5263 0.109334 24.7031 0.28271C24.7214 0.300654 24.7388 0.318995 24.7553 0.338127C24.9018 0.505433 24.9823 0.70942 24.9975 0.917234C25.0011 0.969485 25.0009 1.02239 24.9963 1.0753C24.9931 1.11304 24.9877 1.15065 24.98 1.18799L21.0978 21.5576C21.0354 21.8848 20.8127 22.1587 20.505 22.2863C20.3829 22.337 20.254 22.3619 20.1258 22.3619ZM13.8361 15.9102L19.4354 19.7082L22.4562 3.85843L11.546 14.3568L13.8097 15.8924C13.8188 15.898 13.8275 15.9041 13.8361 15.9102ZM9.17484 15.0656L9.92455 17.9064L11.5398 16.7441L9.42474 15.3093C9.32644 15.2428 9.24226 15.1599 9.17484 15.0656ZM3.71244 10.1314L7.86581 11.7193C8.16335 11.8331 8.38792 12.0832 8.46919 12.3912L8.99592 14.3874C9.02007 14.1571 9.12444 13.9405 9.29399 13.7773L19.6898 3.77398L3.71244 10.1314Z" fill="white"/>
        </svg>

        <div class = "ml-2">Подключить <br class = "card-br"/> тариф +100 р.мес</div>
        </VBtn>
      </VCard>
    </VCol>
  </VRow>
  <div class = "divider_line mt-12 mb-2"></div>
    </VContainer>
<v-container>
    <VRow class = "justify-center">
      <VCol cols = 11 md = 4 class = "violet-bg rounded-lg">
            <div class = "right-card">
            <p class = "right-card__title pt-2 pl-2">Узнайте о последних обновлениях и новостях в сфере автоматизации продаж</p>
            <div class = "right-card__divider"></div>
            
            <div class = "d-sm-flex d-none align-start justify-start ">
                <div>
                    <svg width="14" height="14" viewBox="0 0 14 14" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <circle cx="7" cy="7" r="7" fill="white" fill-opacity="0.26"/>
                        <path d="M10.8881 6.99924C10.8881 9.14701 9.14701 10.8881 6.99924 10.8881C4.85147 10.8881 3.11035 9.14701 3.11035 6.99924C3.11035 4.85147 4.85147 3.11035 6.99924 3.11035C9.14701 3.11035 10.8881 4.85147 10.8881 6.99924Z" fill="white" fill-opacity="0.89"/>
                    </svg>
                </div>
                <p class = "ml-2 right-card__information-text">Будьте в курсе новых функций, акций и новинок, которые помогут вам оптимизировать процессы продаж и увеличить эффективность вашего бизнеса. </p>
            </div>
            <div class = "d-flex align-center justify-sm-end justify-center">
                <button class = "right-card__opinion-button">Ваше мнение и пожелания</button>
            </div>
            <div class = "d-sm-block d-none"><textarea class = "right-card__textarea" placeholder= "Введите ваши пожелания" name="" id="" cols="20" rows="10"></textarea>
                
                <button class = "right-card__textarea-svg">

                <svg width="23" height="25" viewBox="0 0 23 19" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M20.8159 7.32493L3.36306 0.32381C2.6278 0.0288319 1.79714 0.158594 1.1953 0.662287C0.593464 1.16606 0.341744 1.94227 0.538456 2.68796L2.09191 8.08981L9.69783 8.30986C10.0478 8.30986 10.3316 8.8517 10.3316 9.19009C10.3316 9.52845 10.0479 10.0703 9.69783 10.0703H2.09191L0.538456 15.6922C0.341744 16.4379 0.593422 17.2141 1.1953 17.7179C1.79836 18.2226 2.62911 18.3507 3.3631 18.0563L20.8159 11.0552C21.6105 10.7365 22.1041 10.0218 22.1041 9.19009C22.1041 8.35838 21.6105 7.64364 20.8159 7.32493Z" fill="#B0B0B0"/>
                </svg></button>
                <button class = "right-card__textarea-svg">
                <svg width="26" height="23" viewBox="0 0 26 25" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M22.518 2.86581C21.0331 1.31904 18.6982 0.0633221 16.0078 2.86581L5.1011 14.2262C5.01712 14.3047 4.01333 15.2865 3.97801 16.7106C3.95603 17.5903 4.30214 18.4103 5.00849 19.1461C5.61123 19.7739 6.33249 20.1001 7.0922 20.0903C8.46879 20.0731 9.49534 18.9924 9.60679 18.8697L17.8122 10.3233C18.119 10.0036 18.1198 9.48697 17.8122 9.16731C17.5053 8.84766 17.0093 8.84766 16.7024 9.16731L8.48449 17.7276C8.28906 17.9369 7.6769 18.4503 7.0663 18.4552C6.73197 18.4577 6.42196 18.3048 6.11823 17.9893C5.72582 17.5805 5.53903 17.1799 5.54688 16.7621C5.56022 16.0206 6.17866 15.4157 6.18494 15.4083L17.1176 4.02179C18.1787 2.91731 19.5184 2.05237 21.4082 4.02179C22.1004 4.74285 22.4434 5.49007 22.4301 6.24383C22.4073 7.48239 21.4435 8.42418 21.4333 8.43399L9.17513 21.0599C9.14845 21.0877 7.63295 22.6835 5.78782 22.6966C4.81699 22.7031 3.89482 22.2584 3.04721 21.3763C-0.156457 18.0391 2.84158 14.7085 2.97029 14.5687L12.3984 4.74694C12.7053 4.42729 12.7053 3.91061 12.3984 3.59014C12.0908 3.27048 11.5948 3.2713 11.2887 3.59014L1.84878 13.4234C0.374871 15.0224 -1.48595 18.9662 1.93668 22.5323C3.09665 23.7397 4.40025 24.3447 5.81137 24.3308C8.32124 24.3079 10.2127 22.2944 10.2919 22.2085L22.5148 9.61859C22.5494 9.5867 23.9526 8.24024 23.9989 6.29615C24.028 5.07313 23.5296 3.91878 22.518 2.86581Z" fill="#B0B0B0"/>
                </svg></button>
            </div>
        </div>
        </VCol>
        <VCol cols = 11 md = 8 order-md="first">
        <VRow>
        <VCol v-for="item,x  in News" :key="x">
            <div class = "d-flex align-center justify-start">
            <svg width="33" height="33" viewBox="0 0 33 33" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <rect width="32.9079" height="32.9079" rx="5" fill="#EFE5FF"/>
                    <g clip-path="url(#clip0_1425_594)">
                    <path d="M23.2292 26H9.96875C8.33158 26 7 24.6684 7 23.0312V9.17708C7 7.97613 7.97613 7 9.17708 7H19.0729C20.2739 7 21.25 7.97613 21.25 9.17708V9.375H23.8229C25.0239 9.375 26 10.3511 26 11.5521V23.0312C26 24.5481 24.8568 25.8021 23.3867 25.9786C23.3368 25.9929 23.2838 26 23.2292 26ZM21.25 10.5625V23.0312C21.25 24.0137 22.0488 24.8125 23.0312 24.8125C24.0137 24.8125 24.8125 24.0137 24.8125 23.0312V11.5521C24.8125 11.0066 24.3684 10.5625 23.8229 10.5625H21.25ZM9.17708 8.1875C8.63163 8.1875 8.1875 8.63163 8.1875 9.17708V23.0312C8.1875 24.0137 8.98629 24.8125 9.96875 24.8125H20.6578C20.2842 24.3161 20.0625 23.6986 20.0625 23.0312V9.17708C20.0625 8.63163 19.6184 8.1875 19.0729 8.1875H9.17708Z" fill="#9155FD"/>
                    <path d="M13.5312 14.125H9.96875C9.641 14.125 9.375 13.859 9.375 13.5312V9.96875C9.375 9.641 9.641 9.375 9.96875 9.375H13.5312C13.859 9.375 14.125 9.641 14.125 9.96875V13.5312C14.125 13.859 13.859 14.125 13.5312 14.125ZM10.5625 12.9375H12.9375V10.5625H10.5625V12.9375Z" fill="#9155FD"/>
                    <path d="M18.2819 11.3545H16.3027C15.975 11.3545 15.709 11.0885 15.709 10.7607C15.709 10.433 15.975 10.167 16.3027 10.167H18.2819C18.6097 10.167 18.8757 10.433 18.8757 10.7607C18.8757 11.0885 18.6097 11.3545 18.2819 11.3545Z" fill="#9155FD"/>
                    <path d="M18.2812 16.8955H9.96875C9.641 16.8955 9.375 16.6295 9.375 16.3018C9.375 15.974 9.641 15.708 9.96875 15.708H18.2812C18.609 15.708 18.875 15.974 18.875 16.3018C18.875 16.6295 18.609 16.8955 18.2812 16.8955Z" fill="#9155FD"/>
                    <path d="M18.2812 19.8643H9.96875C9.641 19.8643 9.375 19.5983 9.375 19.2705C9.375 18.9428 9.641 18.6768 9.96875 18.6768H18.2812C18.609 18.6768 18.875 18.9428 18.875 19.2705C18.875 19.5983 18.609 19.8643 18.2812 19.8643Z" fill="#9155FD"/>
                    <path d="M18.2812 22.833H9.96875C9.641 22.833 9.375 22.567 9.375 22.2393C9.375 21.9115 9.641 21.6455 9.96875 21.6455H18.2812C18.609 21.6455 18.875 21.9115 18.875 22.2393C18.875 22.567 18.609 22.833 18.2812 22.833Z" fill="#9155FD"/>
                    </g>
                    <defs>
                    <clipPath id="clip0_1425_594">
                    <rect width="19" height="19" fill="white" transform="translate(7 7)"/>
                    </clipPath>
                    </defs>
            </svg>
            <h1 class = "ml-2 news-anons__title">Новости и анонсы:</h1>
        </div>


        <div class = "news-card">
            <p class = "news-card_data">{{item.data}} | Обновление — {{item.version}}</p>
            <div class = "news-card__sections">
                <div class = "news-card__sections_text">Разделы:</div>
                <div class = "news-card__sections-ad">Объявления</div>
                <div class = "news-card__sections-auto">Автоответчик</div>
            </div>
            <div class = "mt-3 rounded-lg pa-4 news-card__white"> 
                <h2 class = "news-card__title">Новое</h2>
                <div class = "d-flex align-start justify-start">
                    <div>
                       <svg width="14" height="14" viewBox="0 0 14 14" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <circle cx="7" cy="7" r="7" fill="#9155FD" fill-opacity="0.16"/>
                            <path d="M10.8872 6.99924C10.8872 9.14701 9.14604 10.8881 6.99826 10.8881C4.85049 10.8881 3.10937 9.14701 3.10937 6.99924C3.10937 4.85147 4.85049 3.11035 6.99826 3.11035C9.14604 3.11035 10.8872 4.85147 10.8872 6.99924Z" fill="#9155FD" fill-opacity="0.66"/>
                        </svg> 
                    </div>
                    <p class = "ml-2 news-card__information-text">{{ item.new_information }}</p>
                </div>
                <h2 class = "news-card__title">Исправлено</h2>
                <div class = "d-flex align-start justify-start">
                    <div>
                       <svg width="14" height="14" viewBox="0 0 14 14" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <circle cx="7" cy="7" r="7" fill="#9155FD" fill-opacity="0.16"/>
                            <path d="M10.8872 6.99924C10.8872 9.14701 9.14604 10.8881 6.99826 10.8881C4.85049 10.8881 3.10937 9.14701 3.10937 6.99924C3.10937 4.85147 4.85049 3.11035 6.99826 3.11035C9.14604 3.11035 10.8872 4.85147 10.8872 6.99924Z" fill="#9155FD" fill-opacity="0.66"/>
                        </svg> 
                    </div>
                    <p class = "ml-2 news-card__information-text">{{ item.fixed_1 }}</p>
                </div>
                <div class = "d-flex align-start justify-start">
                    <div>
                       <svg width="14" height="14" viewBox="0 0 14 14" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <circle cx="7" cy="7" r="7" fill="#9155FD" fill-opacity="0.16"/>
                            <path d="M10.8872 6.99924C10.8872 9.14701 9.14604 10.8881 6.99826 10.8881C4.85049 10.8881 3.10937 9.14701 3.10937 6.99924C3.10937 4.85147 4.85049 3.11035 6.99826 3.11035C9.14604 3.11035 10.8872 4.85147 10.8872 6.99924Z" fill="#9155FD" fill-opacity="0.66"/>
                        </svg> 
                    </div>
                    <p class = "ml-2 news-card__information-text">{{ item.fixed_2 }}</p>
                </div>
            </div>
        </div>
        </VCol></VRow>
        </VCol>
        
      </VRow>
        
  </v-container>

  <v-container>
    <VRow>
      <VCol cols = 12 md = 4>
        <div class = "ad px-12 py-16 d-flex align-center justify-center rounded-lg">
          рекламный банер
        </div>
      </VCol>
      <VCol cols = 12 md = 4>
        <div class = "ad px-12 py-16 d-flex align-center justify-center rounded-lg">
          рекламный банер
        </div>
      </VCol>
      <VCol cols = 12 md = 4>
        <div class = "ad px-12 py-16 d-flex align-center justify-center rounded-lg">
          рекламный банер
        </div>
      </VCol>
    </VRow>
  </v-container>
    
</template>
<style>
html, body {width:100%; overflow-x:hidden}
.top-card{
  display: flex;
  justify-content: flex-start;
  align-items: center;
  flex-wrap: nowrap;
  height: 81px;
  flex-shrink: 0;
  width: 100%;
  background: rgba(239, 230, 251, 0.48);
  border: 1px solid #D8E2EF;
  line-height: 27.65px;
}
  .top-card__h1{
    color: #9155FD;
    font-size: 23px;
    font-weight: 700;
  }
  .top-card__text{
    margin-left: 64px;
    color: #5B5B5B;
    font-size: 23px;
    font-weight: 400;
  }
  .news-card__sections{
    display: flex;
    align-items: center;
    justify-content: left;
  }
  .news-card__title{
    color: #9155FD;
    font-size: 20px;
    font-weight: 500;
  }
  .news-anons__title{
    color: #9155FD;
    font-size: 23px;
    font-weight: 700;
  }
.avito-card__title-text{
    color: #9155FD !important;
    font-weight: 900 !important;
    font-size: 23px;
}
.avito-card__text{
    font-size: 16px !important;
}
.list-items{
    font-size: 19px;
}
.text_wrap__btn{
    background: linear-gradient(89.18deg, #9155FD 4.92%, #AE82FE 49.04%, #9155FD 96.84%);
    flex-wrap: nowrap !important;
}
.divider_line{
    background: rgba(145, 85, 253, 0.27);
    width: 100%;
    height: 2px;
}
.right-card-news{
    background: linear-gradient(111.31deg, #975EFD -1.55%, #C09EFF -1.54%, #9155FD 88.12%);
    width: auto;
    color: #FFFFFF;
}
.right-card__news-button{
    background: #E9DDFF;
    color: #9155FD;
    font-weight: 300;
    font-size: 16px;
}
.ad{
  background: linear-gradient(111.31deg, #975EFD -1.55%, #C09EFF -1.54%, #9155FD 88.12%);
  color: #FFFFFF;
}
.card-br{
  display: none;
}

.news-card__sections-ad{
    background: #E9DDFF;
    font-size: 16px;
    color: #9155FD;
    border-radius: 26px;
    padding: 5px 20px;
    margin-left: 10px;
}
.news-card__sections-auto{
    background: #D3E6FF;
    font-size: 16px;
    color: #2C7BE5;
    border-radius: 26px;
    padding: 5px 20px;
    margin-left: 10px;
}

.news_cards{
    display: flex;
    align-items: flex-start;
    justify-content: center;
}
.news-card__white{
  background: #FFFFFF;
}
.violet-bg{
  background: linear-gradient(111.31deg, #975EFD -1.55%, #C09EFF -1.54%, #9155FD 88.12%);
  color: #FFFFFF;
  font-weight: 300;
}

.right-card__textarea{
    background-color: #FFFFFF;
    border-radius: 17px;
    width: 100%;
    padding: 15px;
    margin-top: 30px;
}
.right-card__textarea-svg{
    float: right;
    margin: -40px 10px 10px 10px;
    position: relative;
}
.right-card__opinion-button{
    background: #E9DDFF;
    border-radius: 26px;
    color: #9155FD;
    font-weight: 300;
    padding: 7px 10px;
    font-size: 16px;
    float: right;
}
.right-card__textarea:focus {
    outline: none !important;
    border: none;
}
@media (max-width: 1280px) {
  .card-br{
    display: block;
  }
}
@media (max-width: 785px) {
  .card-br{
    display: none;
  }
  .news-block{
    display: block;
  }
}
@media(max-width: 750px){
    .news_cards{
        display: block;
    }
    .right-card__order{
        max-width: 100% !important;
        margin-left: 0px;
        margin-bottom: 20px;
    }
}

@media (max-width: 960px) {  
  .top-card__text{
    margin-left: 10px;
    color: #9155FD;
    font-size: 23px;
    font-weight: 700;
    margin-left: 5px;
    text-align: center;
  }
  .right-card-news{
    margin-left: 0px;
    margin-bottom: 15px;
  }
}
@media (max-width: 420px) {
  .news-card__sections{
    display: grid;
    grid-template-columns: repeat(45%);
  }
  .news-card__sections-ad, .news-card__sections-auto{
    margin: 5px 0px 5px 0px;
  }
}
@media (max-width: 340px) {
  .card-br{
    display: block;
  }
}
</style>