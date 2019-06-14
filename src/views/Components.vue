<template>
    <div>
        <hero></hero>
        <!--<basic-elements></basic-elements>
        <inputs></inputs>
        <custom-controls></custom-controls>
        <navigation></navigation>
        <javascript-components></javascript-components>
        -->
        <prologue></prologue>
        <carousel></carousel>
        <client-info></client-info>
        <examples></examples>
        <team></team>

    </div>
</template>
<script>
import Hero from "./components/Hero";
import BasicElements from "./components/BasicElements";
import Inputs from "./components/Inputs";
import CustomControls from "./components/CustomControls";
import Navigation from "./components/Navigation";
import JavascriptComponents from "./components/JavascriptComponents";
import Carousel from "./components/Carousel";
import Icons from "./components/Icons";
import Examples from "./components/Examples";
import DownloadSection from "./components/DownloadSection";
import Prologue from "./components/Prologue";
import ClientInfo from "./components/ClientInfo";
import Fonctionnalites from "./components/Fontionnalites";
import Team from "./components/Team";

export default {
  name: "components",
  components: {
    Hero,
    BasicElements,
    Inputs,
    CustomControls,
    Navigation,
    JavascriptComponents,
    Carousel,
    ClientInfo,
    Prologue,
    Fonctionnalites,
    Team,
    Icons,
    Examples,
    DownloadSection
  }
};
</script>
