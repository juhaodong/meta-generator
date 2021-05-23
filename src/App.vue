<template>
  <v-app>
    <v-navigation-drawer permanent app>
      <v-list-item>
        <v-list-item-content>
          <v-list-item-title class="title">
            生成器生成器
          </v-list-item-title>
          <v-list-item-subtitle>
            一个生成各种生成器的生成器
          </v-list-item-subtitle>
        </v-list-item-content>
      </v-list-item>

      <v-divider></v-divider>

      <v-list
          subheader
          nav
      >
        <v-subheader>生成生成器</v-subheader>
        <v-divider></v-divider>
        <v-list-item
            link
            to="/create"
        >
          <v-list-item-content>
            <v-list-item-title>生成</v-list-item-title>
            <v-list-item-subtitle>重新<b>生成</b>一个生成器</v-list-item-subtitle>
          </v-list-item-content>
        </v-list-item>
        <v-list-item
            link
        >
          <v-list-item-content>
            <v-list-item-title>导入</v-list-item-title>
            <v-list-item-subtitle>导入现有的生成器</v-list-item-subtitle>
          </v-list-item-content>
        </v-list-item>
        <v-divider>s</v-divider>
        <v-subheader>已经生成的生成器</v-subheader>
        <v-divider></v-divider>
        <v-list-item
            link
        >
          <v-list-item-content>
            <v-list-item-title>彩虹屁生成器</v-list-item-title>
          </v-list-item-content>
        </v-list-item>
        <v-list-item
            link
        >
          <v-list-item-content>
            <v-list-item-title>彩虹屁生成器</v-list-item-title>
          </v-list-item-content>
        </v-list-item>
      </v-list>
    </v-navigation-drawer>
    <v-main>
      <router-view/>
    </v-main>

  </v-app>
</template>

