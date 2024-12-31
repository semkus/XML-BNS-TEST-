<?xml version="1.0" encoding="utf-16"?>
<!--C:/Users/DXUSER~1/AppData/Local/Temp/g32ED0E.tmp/skill3_contextscriptdata_swordmaster_contextsimplemode_g1.xml-->
<table release-module="CombatData" release-side="client" version="0.48">
  <contextscript alias="SwordMaster_ContextSimpleMode_G1_Var_1" context-simple-mode="y" job="귀검사" job-style-2="advanced-1">
    <stance abnormal-flag="PeaceArea">
      <layer>
        <decision>
          <result cmd-key-down="501" cmd-key-left="501" cmd-key-right="501" control-mode="classic" skillbar-1="501" skillbar-2="501" skillbar-3="501" skillbar-4="501"/>
          <result cmd-key-down="501" cmd-key-left="501" cmd-key-right="501" control-mode="bns" skillbar-1="501" skillbar-2="501" skillbar-3="501" skillbar-4="501"/>
        </decision>
      </layer>
    </stance>
    <stance abnormal-flag="Struggle">
      <layer>
        <decision>
          <condition skill="5920741"/>
          <result context-1="5920741" control-mode="classic"/>
          <result context-1="5920741" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="5920742"/>
          <result context-2="5920742" control-mode="classic"/>
          <result context-2="5920742" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="5920743"/>
          <result control-mode="classic" skillbar-1="5920743"/>
          <result control-mode="bns" skillbar-1="5920743"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="5920744"/>
          <result control-mode="classic" skillbar-2="5920744"/>
          <result control-mode="bns" skillbar-2="5920744"/>
        </decision>
      </layer>
    </stance>
    <stance link="mount">
      <layer>
        <decision>
          <condition skill="160213"/>
          <result control-mode="classic" skillbar-2="160213"/>
          <result control-mode="bns" skillbar-2="160213"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <result control-mode="classic" skillbar-2="160217"/>
          <result control-mode="bns" skillbar-2="160217"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160012"/>
          <result control-mode="classic" stance="160012"/>
          <result control-mode="bns" stance="160012"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160622"/>
          <result control-mode="classic" skillbar-5="160622"/>
          <result control-mode="bns" skillbar-5="160622"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160900"/>
          <result cmd-key-down="160900" control-mode="classic"/>
          <result cmd-key-down="160900" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <result cmd-key-down="160520" cmd-key-left="160500" cmd-key-right="160510" control-mode="classic" skillbar-1="501" skillbar-2="501" skillbar-3="501" skillbar-4="501" skillbar-5="501" skillbar-6="501" skillbar-7="501" skillbar-8="501"/>
          <result cmd-key-down="160520" cmd-key-left="160500" cmd-key-right="160510" control-mode="bns" skillbar-1="501" skillbar-2="501" skillbar-3="501" skillbar-4="501" skillbar-5="501" skillbar-6="501" skillbar-7="501" skillbar-8="501"/>
        </decision>
      </layer>
    </stance>
    <stance abnormal-flag="stun">
      <layer>
        <decision>
          <condition skill="160010"/>
          <result control-mode="classic" stance="160010"/>
          <result control-mode="bns" stance="160010"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163211"/>
          <result control-mode="classic" skillbar-4="163211"/>
          <result control-mode="bns" skillbar-4="163211"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160900"/>
          <result cmd-key-down="160900" control-mode="classic"/>
          <result cmd-key-down="160900" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <result cmd-key-down="160520" cmd-key-left="160500" cmd-key-right="160510" control-mode="classic" skillbar-1="501" skillbar-2="501" skillbar-3="501" skillbar-4="501"/>
          <result cmd-key-down="160520" cmd-key-left="160500" cmd-key-right="160510" control-mode="bns" skillbar-1="501" skillbar-2="501" skillbar-3="501" skillbar-4="501"/>
        </decision>
      </layer>
    </stance>
    <stance abnormal-flag="kneel">
      <layer>
        <decision>
          <condition skill="160010"/>
          <result control-mode="classic" stance="160010"/>
          <result control-mode="bns" stance="160010"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160100"/>
          <result context-3="160100" control-mode="classic" skillbar-ui-effect="key-change"/>
          <result context-3="160100" control-mode="bns" skillbar-ui-effect="key-change"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163211"/>
          <result control-mode="classic" skillbar-4="163211"/>
          <result control-mode="bns" skillbar-4="163211"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160900"/>
          <result cmd-key-down="160900" control-mode="classic"/>
          <result cmd-key-down="160900" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <result cmd-key-down="160520" cmd-key-left="160500" cmd-key-right="160510" control-mode="classic" skillbar-1="501" skillbar-2="501" skillbar-3="501" skillbar-4="501"/>
          <result cmd-key-down="160520" cmd-key-left="160500" cmd-key-right="160510" control-mode="bns" skillbar-1="501" skillbar-2="501" skillbar-3="501" skillbar-4="501"/>
        </decision>
      </layer>
    </stance>
    <stance abnormal-flag="swoon">
      <layer>
        <decision>
          <condition skill="160010"/>
          <result control-mode="classic" stance="160010"/>
          <result control-mode="bns" stance="160010"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160100"/>
          <result context-3="160100" control-mode="classic" skillbar-ui-effect="key-change"/>
          <result context-3="160100" control-mode="bns" skillbar-ui-effect="key-change"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163211"/>
          <result control-mode="classic" skillbar-4="163211"/>
          <result control-mode="bns" skillbar-4="163211"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160900"/>
          <result cmd-key-down="160900" control-mode="classic"/>
          <result cmd-key-down="160900" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <result cmd-key-down="160520" cmd-key-left="160500" cmd-key-right="160510" control-mode="classic" skillbar-1="501" skillbar-2="501" skillbar-3="501" skillbar-4="501"/>
          <result cmd-key-down="160520" cmd-key-left="160500" cmd-key-right="160510" control-mode="bns" skillbar-1="501" skillbar-2="501" skillbar-3="501" skillbar-4="501"/>
        </decision>
      </layer>
    </stance>
    <stance abnormal-flag="down">
      <layer>
        <decision>
          <condition skill="160010"/>
          <result control-mode="classic" stance="160010"/>
          <result control-mode="bns" stance="160010"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160100"/>
          <result context-3="160100" control-mode="classic" skillbar-ui-effect="key-change"/>
          <result context-3="160100" control-mode="bns" skillbar-ui-effect="key-change"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163211"/>
          <result control-mode="classic" skillbar-4="163211"/>
          <result control-mode="bns" skillbar-4="163211"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160900"/>
          <result cmd-key-down="160900" control-mode="classic"/>
          <result cmd-key-down="160900" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <result cmd-key-down="160520" cmd-key-left="160500" cmd-key-right="160510" control-mode="classic" skillbar-1="160140" skillbar-2="160200" skillbar-ui-effect="key-change"/>
          <result cmd-key-down="160520" cmd-key-left="160500" cmd-key-right="160510" control-mode="bns" skillbar-1="160140" skillbar-2="160200" skillbar-ui-effect="key-change"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <result control-mode="classic" skillbar-1="501" skillbar-2="501" skillbar-3="501" skillbar-4="501"/>
          <result control-mode="bns" skillbar-1="501" skillbar-2="501" skillbar-3="501" skillbar-4="501"/>
        </decision>
      </layer>
    </stance>
    <stance abnormal-flag="fast-freezing">
      <layer>
        <decision>
          <condition skill="160011"/>
          <result control-mode="classic" stance="160011"/>
          <result control-mode="bns" stance="160011"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="65013"/>
          <result context-3="65013" control-mode="classic"/>
          <result context-3="65013" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160900"/>
          <result cmd-key-down="160900" control-mode="classic"/>
          <result cmd-key-down="160900" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <result cmd-key-down="160520" cmd-key-left="160500" cmd-key-right="160510" control-mode="classic" skillbar-1="501" skillbar-2="501" skillbar-3="501" skillbar-4="501" skillbar-ui-effect="key-change"/>
          <result cmd-key-down="160520" cmd-key-left="160500" cmd-key-right="160510" control-mode="bns" skillbar-1="501" skillbar-2="501" skillbar-3="501" skillbar-4="501" skillbar-ui-effect="key-change"/>
        </decision>
      </layer>
    </stance>
    <stance link="inhalation-catch">
      <layer>
        <decision>
          <condition skill="160014"/>
          <result control-mode="classic" skillbar-ui-effect="key-change" stance="160014"/>
          <result control-mode="bns" skillbar-ui-effect="key-change" stance="160014"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160624"/>
          <result control-mode="classic" skillbar-5="160624"/>
          <result control-mode="bns" skillbar-5="160624"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160150"/>
          <result control-mode="classic" skillbar-1="160150" skillbar-ui-effect="key-change"/>
          <result control-mode="bns" skillbar-1="160150" skillbar-ui-effect="key-change"/>
        </decision>
        <decision>
          <condition skill="160130"/>
          <result control-mode="classic" skillbar-1="160130" skillbar-ui-effect="key-change"/>
          <result control-mode="bns" skillbar-1="160130" skillbar-ui-effect="key-change"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160210"/>
          <result control-mode="classic" skillbar-2="160210"/>
          <result control-mode="bns" skillbar-2="160210"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160190"/>
          <result control-mode="classic" skillbar-2="160190" skillbar-ui-effect="key-change"/>
          <result control-mode="bns" skillbar-2="160190" skillbar-ui-effect="key-change"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160230"/>
          <result control-mode="classic" skillbar-3="160230" skillbar-ui-effect="key-change"/>
          <result control-mode="bns" skillbar-3="160230" skillbar-ui-effect="key-change"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160250"/>
          <result control-mode="classic" skillbar-4="160250" skillbar-ui-effect="key-change"/>
          <result control-mode="bns" skillbar-4="160250" skillbar-ui-effect="key-change"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160560"/>
          <result control-mode="classic" skillbar-6="160560" skillbar-ui-effect="key-change"/>
          <result control-mode="bns" skillbar-6="160560" skillbar-ui-effect="key-change"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160090"/>
          <result context-3="160090" control-mode="classic" skillbar-ui-effect="key-change"/>
          <result context-3="160090" control-mode="bns" skillbar-ui-effect="key-change"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160460"/>
          <result context-2="160460" control-mode="classic" skillbar-ui-effect="event"/>
          <result context-2="160460" control-mode="bns" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160310"/>
          <result context-1="160310" control-mode="classic" skillbar-ui-effect="event"/>
          <result context-1="160310" control-mode="bns" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163451"/>
          <result cmd-key-left="163451" control-mode="classic"/>
          <result cmd-key-left="163451" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163461"/>
          <result cmd-key-right="163461" control-mode="classic"/>
          <result cmd-key-right="163461" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160881"/>
          <result cmd-key-left="160881" control-mode="classic"/>
          <result cmd-key-left="160881" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160891"/>
          <result cmd-key-right="160891" control-mode="classic"/>
          <result cmd-key-right="160891" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160521"/>
          <result cmd-key-down="160521" control-mode="classic"/>
          <result cmd-key-down="160521" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160901"/>
          <result cmd-key-down="160901" control-mode="classic"/>
          <result cmd-key-down="160901" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160214"/>
          <result control-mode="classic" skillbar-2="160214"/>
          <result control-mode="bns" skillbar-2="160214"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <result cmd-key-left="160501" cmd-key-right="160511" control-mode="classic" skillbar-1="501" skillbar-3="501" skillbar-4="501" skillbar-5="501" skillbar-6="501" skillbar-7="501" skillbar-8="501"/>
          <result cmd-key-left="160501" cmd-key-right="160511" control-mode="bns" skillbar-1="501" skillbar-3="501" skillbar-4="501" skillbar-5="501" skillbar-6="501" skillbar-7="501" skillbar-8="501"/>
        </decision>
      </layer>
    </stance>
    <stance link="catch-none-human">
      <layer>
        <decision>
          <condition skill="160091"/>
          <result context-3="160091" control-mode="classic" skillbar-ui-effect="key-change"/>
          <result context-3="160091" control-mode="bns" skillbar-ui-effect="key-change"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160461"/>
          <result context-2="160461" control-mode="classic" skillbar-ui-effect="event"/>
          <result context-2="160461" control-mode="bns" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160311"/>
          <result context-1="160311" control-mode="classic" skillbar-ui-effect="event"/>
          <result context-1="160311" control-mode="bns" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163452"/>
          <result cmd-key-left="163452" control-mode="classic"/>
          <result cmd-key-left="163452" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163462"/>
          <result cmd-key-right="163462" control-mode="classic"/>
          <result cmd-key-right="163462" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160902"/>
          <result cmd-key-down="160902" control-mode="classic"/>
          <result cmd-key-down="160902" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160522"/>
          <result cmd-key-down="160522" control-mode="classic"/>
          <result cmd-key-down="160522" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <result cmd-key-left="160502" cmd-key-right="160512" control-mode="classic" skillbar-1="160131" skillbar-2="160191" skillbar-3="160231" skillbar-4="160251" skillbar-5="501" skillbar-6="160561" skillbar-7="501" skillbar-8="501"/>
          <result cmd-key-left="160502" cmd-key-right="160512" control-mode="bns" skillbar-1="160131" skillbar-2="160191" skillbar-3="160231" skillbar-4="160251" skillbar-5="501" skillbar-6="160561" skillbar-7="501" skillbar-8="501"/>
        </decision>
      </layer>
    </stance>
    <stance link="catch">
      <layer>
        <decision>
          <condition skill="160013"/>
          <result control-mode="classic" skillbar-ui-effect="key-change" stance="160013"/>
          <result control-mode="bns" skillbar-ui-effect="key-change" stance="160013"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160623"/>
          <result control-mode="classic" skillbar-5="160623"/>
          <result control-mode="bns" skillbar-5="160623"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160211"/>
          <result control-mode="classic" skillbar-2="160211"/>
          <result control-mode="bns" skillbar-2="160211"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160900"/>
          <result cmd-key-down="160900" control-mode="classic"/>
          <result cmd-key-down="160900" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <result cmd-key-down="160520" cmd-key-left="160500" cmd-key-right="160510" control-mode="classic" skillbar-1="160151" skillbar-2="160215"/>
          <result cmd-key-down="160520" cmd-key-left="160500" cmd-key-right="160510" control-mode="bns" skillbar-1="160151" skillbar-2="160215"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <result control-mode="classic" skillbar-1="501" skillbar-2="501" skillbar-3="501" skillbar-4="501" skillbar-5="501" skillbar-6="501" skillbar-7="501" skillbar-8="501"/>
          <result control-mode="bns" skillbar-1="501" skillbar-2="501" skillbar-3="501" skillbar-4="501" skillbar-5="501" skillbar-6="501" skillbar-7="501" skillbar-8="501"/>
        </decision>
      </layer>
    </stance>
    <stance link="inhalation">
      <layer>
        <decision>
          <condition skill="160212"/>
          <result control-mode="classic" skillbar-2="160212"/>
          <result control-mode="bns" skillbar-2="160212"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160900"/>
          <result cmd-key-down="160900" control-mode="classic"/>
          <result cmd-key-down="160900" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <result cmd-key-down="160520" cmd-key-left="160500" cmd-key-right="160510" control-mode="classic" skillbar-1="160152" skillbar-2="160216"/>
          <result cmd-key-down="160520" cmd-key-left="160500" cmd-key-right="160510" control-mode="bns" skillbar-1="160152" skillbar-2="160216"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <result control-mode="classic" skillbar-1="501" skillbar-2="501" skillbar-3="501" skillbar-4="501"/>
          <result control-mode="bns" skillbar-1="501" skillbar-2="501" skillbar-3="501" skillbar-4="501"/>
        </decision>
      </layer>
    </stance>
    <stance link="range-catch">
      <layer>
        <decision>
          <condition skill="160015"/>
          <result control-mode="classic" stance="160015"/>
          <result control-mode="bns" stance="160015"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160625"/>
          <result control-mode="classic" skillbar-5="160625"/>
          <result control-mode="bns" skillbar-5="160625"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160900"/>
          <result cmd-key-down="160900" control-mode="classic"/>
          <result cmd-key-down="160900" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <result cmd-key-down="160520" cmd-key-left="160500" cmd-key-right="160510" control-mode="classic" skillbar-1="501" skillbar-2="501" skillbar-3="501" skillbar-4="501" skillbar-5="501" skillbar-6="501" skillbar-7="501" skillbar-8="501"/>
          <result cmd-key-down="160520" cmd-key-left="160500" cmd-key-right="160510" control-mode="bns" skillbar-1="501" skillbar-2="501" skillbar-3="501" skillbar-4="501" skillbar-5="501" skillbar-6="501" skillbar-7="501" skillbar-8="501"/>
        </decision>
      </layer>
    </stance>
    <stance stance="검술">
      <layer>
        <decision>
          <condition skill="183005"/>
          <result context-3="183005" context-ui-effect="key-change" control-mode="classic"/>
          <result context-3="183005" context-ui-effect="key-change" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="66113"/>
          <result context-3="66113" control-mode="classic" skillbar-ui-effect="key-change"/>
          <result context-3="66113" control-mode="bns" skillbar-ui-effect="key-change"/>
        </decision>
        <decision>
          <condition skill="66114"/>
          <result context-3="66114" control-mode="classic" skillbar-ui-effect="key-change"/>
          <result context-3="66114" control-mode="bns" skillbar-ui-effect="key-change"/>
        </decision>
        <decision>
          <condition skill="65014"/>
          <result context-3="65014" control-mode="classic" skillbar-1="501" skillbar-2="501" skillbar-3="501" skillbar-4="501" skillbar-ui-effect="key-change"/>
          <result context-3="65014" control-mode="bns" skillbar-1="501" skillbar-2="501" skillbar-3="501" skillbar-4="501" skillbar-ui-effect="key-change"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="65013"/>
          <result context-3="65013" control-mode="classic" skillbar-1="501" skillbar-2="501" skillbar-3="501" skillbar-4="501" skillbar-ui-effect="key-change"/>
          <result context-3="65013" control-mode="bns" skillbar-1="501" skillbar-2="501" skillbar-3="501" skillbar-4="501" skillbar-ui-effect="key-change"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160042"/>
          <result context-2="160042" control-mode="classic"/>
          <result context-2="160042" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160041"/>
          <result context-2="160041" context-ui-effect="event" control-mode="classic"/>
          <result context-2="160041" context-ui-effect="event" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160040"/>
          <result context-2="160040" control-mode="classic"/>
          <result context-2="160040" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160032"/>
          <result context-2="160032" control-mode="classic"/>
          <result context-2="160032" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160031"/>
          <result context-2="160031" control-mode="classic"/>
          <result context-2="160031" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160030"/>
          <result context-2="160030" context-ui-effect="event" control-mode="classic"/>
          <result context-2="160030" context-ui-effect="event" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160441"/>
          <result context-2="160441" context-ui-effect="event" control-mode="classic"/>
          <result context-2="160441" context-ui-effect="event" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160440"/>
          <result context-2="160440" context-ui-effect="event" control-mode="classic"/>
          <result context-2="160440" context-ui-effect="event" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160366"/>
          <result context-2="160366" context-ui-effect="event" control-mode="classic"/>
          <result context-2="160366" context-ui-effect="event" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160365"/>
          <result context-2="160365" context-ui-effect="event" control-mode="classic"/>
          <result context-2="160365" context-ui-effect="event" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160364"/>
          <result context-2="160364" context-ui-effect="event" control-mode="classic"/>
          <result context-2="160364" context-ui-effect="event" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160363"/>
          <result context-2="160363" context-ui-effect="event" control-mode="classic"/>
          <result context-2="160363" context-ui-effect="event" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160362"/>
          <result context-2="160362" context-ui-effect="event" control-mode="classic"/>
          <result context-2="160362" context-ui-effect="event" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160361"/>
          <result context-2="160361" context-ui-effect="event" control-mode="classic"/>
          <result context-2="160361" context-ui-effect="event" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="27149"/>
          <result control-mode="classic" stance="27149"/>
          <result control-mode="bns" stance="27149"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160470"/>
          <result context-2="160470" context-ui-effect="key-change" control-mode="classic"/>
          <result context-2="160470" context-ui-effect="key-change" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160020"/>
          <result context-3="160020" control-mode="classic"/>
          <result context-3="160020" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160320"/>
          <result context-1="160320" context-ui-effect="key-change" control-mode="classic"/>
          <result context-1="160320" context-ui-effect="key-change" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160321"/>
          <result context-1="160321" context-ui-effect="key-change" control-mode="classic"/>
          <result context-1="160321" context-ui-effect="key-change" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160340"/>
          <result context-1="160340" context-2="160490" context-ui-effect="event" control-mode="classic"/>
          <result context-1="160340" context-2="160490" context-ui-effect="event" control-mode="bns"/>
        </decision>
        <decision>
          <condition skill="160490"/>
          <result context-1="160340" context-2="160490" context-ui-effect="event" control-mode="classic"/>
          <result context-1="160340" context-2="160490" context-ui-effect="event" control-mode="bns"/>
        </decision>
        <decision>
          <condition skill="163290"/>
          <result context-1="163290" context-2="163310" context-ui-effect="event" control-mode="classic"/>
          <result context-1="163290" context-2="163310" context-ui-effect="event" control-mode="bns"/>
        </decision>
        <decision>
          <condition skill="163310"/>
          <result context-1="163290" context-2="163310" context-ui-effect="event" control-mode="classic"/>
          <result context-1="163290" context-2="163310" context-ui-effect="event" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160330"/>
          <result context-1="160330" context-2="160480" context-ui-effect="event" control-mode="classic"/>
          <result context-1="160330" context-2="160480" context-ui-effect="event" control-mode="bns"/>
        </decision>
        <decision>
          <condition skill="160480"/>
          <result context-1="160330" context-2="160480" context-ui-effect="event" control-mode="classic"/>
          <result context-1="160330" context-2="160480" context-ui-effect="event" control-mode="bns"/>
        </decision>
        <decision>
          <condition skill="163320"/>
          <result context-1="163320" context-2="163300" context-ui-effect="event" control-mode="classic"/>
          <result context-1="163320" context-2="163300" context-ui-effect="event" control-mode="bns"/>
        </decision>
        <decision>
          <condition skill="163300"/>
          <result context-1="163320" context-2="163300" context-ui-effect="event" control-mode="classic"/>
          <result context-1="163320" context-2="163300" context-ui-effect="event" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163510"/>
          <result context-1="163510" context-ui-effect="event" control-mode="classic"/>
          <result context-1="163510" context-ui-effect="event" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160350"/>
          <result context-1="160350" context-ui-effect="event" control-mode="classic"/>
          <result context-1="160350" context-ui-effect="event" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160351"/>
          <result context-3="160351" context-ui-effect="event" control-mode="classic"/>
          <result context-3="160351" context-ui-effect="event" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163280"/>
          <result context-1="163280" context-ui-effect="event" control-mode="classic"/>
          <result context-1="163280" context-ui-effect="event" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160261"/>
          <result context-1="160261" context-ui-effect="combo" control-mode="classic"/>
          <result context-1="160261" context-ui-effect="combo" control-mode="bns"/>
        </decision>
        <decision>
          <condition skill="160262"/>
          <result context-1="160262" context-ui-effect="combo" control-mode="classic"/>
          <result context-1="160262" context-ui-effect="combo" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163271"/>
          <result context-1="163271" context-ui-effect="combo" control-mode="classic"/>
          <result context-1="163271" context-ui-effect="combo" control-mode="bns"/>
        </decision>
        <decision>
          <condition skill="163272"/>
          <result context-1="163272" context-ui-effect="combo" control-mode="classic"/>
          <result context-1="163272" context-ui-effect="combo" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160260"/>
          <result context-1="160260" control-mode="classic"/>
          <result context-1="160260" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160760"/>
          <result control-mode="classic" skillbar-6="160760"/>
          <result control-mode="bns" skillbar-6="160760"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160592"/>
          <result control-mode="classic" skillbar-8="160592" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-8="160592" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160591"/>
          <result control-mode="classic" skillbar-8="160591" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-8="160591" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160590"/>
          <result control-mode="classic" skillbar-8="160590"/>
          <result control-mode="bns" skillbar-8="160590"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160552"/>
          <result control-mode="classic" skillbar-7="160552"/>
          <result control-mode="bns" skillbar-7="160552"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160652"/>
          <result control-mode="classic" skillbar-7="160652" skillbar-ui-effect="key-change"/>
          <result control-mode="bns" skillbar-7="160652" skillbar-ui-effect="key-change"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160651"/>
          <result control-mode="classic" skillbar-7="160651" skillbar-ui-effect="key-change"/>
          <result control-mode="bns" skillbar-7="160651" skillbar-ui-effect="key-change"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160650"/>
          <result control-mode="classic" skillbar-7="160650" skillbar-ui-effect="key-change"/>
          <result control-mode="bns" skillbar-7="160650" skillbar-ui-effect="key-change"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160612"/>
          <result control-mode="classic" skillbar-8="160612" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-8="160612" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160611"/>
          <result control-mode="classic" skillbar-8="160611" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-8="160611" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160610"/>
          <result control-mode="classic" skillbar-8="160610"/>
          <result control-mode="bns" skillbar-8="160610"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160617"/>
          <result control-mode="classic" skillbar-8="160617" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-8="160617" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160616"/>
          <result control-mode="classic" skillbar-8="160616" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-8="160616" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160615"/>
          <result control-mode="classic" skillbar-8="160615"/>
          <result control-mode="bns" skillbar-8="160615"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164100"/>
          <result control-mode="classic" Skillbar-1="164100"/>
          <result control-mode="bns" Skillbar-1="164100"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160121"/>
          <result control-mode="classic" skillbar-1="160121"/>
          <result control-mode="bns" skillbar-1="160121"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160120"/>
          <result control-mode="classic" skillbar-1="160120"/>
          <result control-mode="bns" skillbar-1="160120"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="66204" skip-condition-move-check="y" skip-condition-target-check="y"/>
          <result control-mode="classic" special-2="66204" special-ui-effect="event"/>
          <result control-mode="bns" special-2="66204" special-ui-effect="event"/>
        </decision>
        <decision>
          <condition skill="66203" skip-condition-move-check="y" skip-condition-target-check="y"/>
          <result control-mode="classic" special-2="66203" special-ui-effect="event"/>
          <result control-mode="bns" special-2="66203" special-ui-effect="event"/>
        </decision>
        <decision>
          <condition skill="66202" skip-condition-move-check="y" skip-condition-target-check="y"/>
          <result control-mode="classic" special-2="66202" special-ui-effect="event"/>
          <result control-mode="bns" special-2="66202" special-ui-effect="event"/>
        </decision>
        <decision>
          <condition skill="66201" skip-condition-move-check="y" skip-condition-target-check="y"/>
          <result control-mode="classic" special-2="66201" special-ui-effect="event"/>
          <result control-mode="bns" special-2="66201" special-ui-effect="event"/>
        </decision>
        <decision>
          <condition skill="66200" skip-condition-move-check="y" skip-condition-target-check="y"/>
          <result control-mode="classic" special-2="66200" special-ui-effect="event"/>
          <result control-mode="bns" special-2="66200" special-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160635" skip-condition-move-check="y" skip-condition-target-check="y"/>
          <result control-mode="classic" special-2="160635" special-ui-effect="event"/>
          <result control-mode="bns" special-2="160635" special-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160241"/>
          <result control-mode="classic" skillbar-4="160241"/>
          <result control-mode="bns" skillbar-4="160241"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160242"/>
          <result control-mode="classic" skillbar-4="160242"/>
          <result control-mode="bns" skillbar-4="160242"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160240"/>
          <result control-mode="classic" skillbar-4="160240"/>
          <result control-mode="bns" skillbar-4="160240"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160244"/>
          <result control-mode="classic" skillbar-4="160244"/>
          <result control-mode="bns" skillbar-4="160244"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160245"/>
          <result control-mode="classic" skillbar-4="160245"/>
          <result control-mode="bns" skillbar-4="160245"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160243"/>
          <result control-mode="classic" skillbar-4="160243"/>
          <result control-mode="bns" skillbar-4="160243"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163521"/>
          <result control-mode="classic" skillbar-4="163521"/>
          <result control-mode="bns" skillbar-4="163521"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163522"/>
          <result control-mode="classic" skillbar-4="163522"/>
          <result control-mode="bns" skillbar-4="163522"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163520"/>
          <result control-mode="classic" skillbar-4="163520"/>
          <result control-mode="bns" skillbar-4="163520"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163524"/>
          <result control-mode="classic" skillbar-4="163524"/>
          <result control-mode="bns" skillbar-4="163524"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163525"/>
          <result control-mode="classic" skillbar-4="163525"/>
          <result control-mode="bns" skillbar-4="163525"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163523"/>
          <result control-mode="classic" skillbar-4="163523"/>
          <result control-mode="bns" skillbar-4="163523"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163470"/>
          <result control-mode="classic" skillbar-5="163470"/>
          <result control-mode="bns" skillbar-5="163470"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160535"/>
          <result control-mode="classic" skillbar-5="160535"/>
          <result control-mode="bns" skillbar-5="160535"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="66304" skip-condition-move-check="y" skip-condition-target-check="y"/>
          <result control-mode="classic" special-1="66304" special-ui-effect="event"/>
          <result control-mode="bns" special-1="66304" special-ui-effect="event"/>
        </decision>
        <decision>
          <condition skill="66303" skip-condition-move-check="y" skip-condition-target-check="y"/>
          <result control-mode="classic" special-1="66303" special-ui-effect="event"/>
          <result control-mode="bns" special-1="66303" special-ui-effect="event"/>
        </decision>
        <decision>
          <condition skill="66302" skip-condition-move-check="y" skip-condition-target-check="y"/>
          <result control-mode="classic" special-1="66302" special-ui-effect="event"/>
          <result control-mode="bns" special-1="66302" special-ui-effect="event"/>
        </decision>
        <decision>
          <condition skill="66301" skip-condition-move-check="y" skip-condition-target-check="y"/>
          <result control-mode="classic" special-1="66301" special-ui-effect="event"/>
          <result control-mode="bns" special-1="66301" special-ui-effect="event"/>
        </decision>
        <decision>
          <condition skill="66300" skip-condition-move-check="y" skip-condition-target-check="y"/>
          <result control-mode="classic" special-1="66300" special-ui-effect="event"/>
          <result control-mode="bns" special-1="66300" special-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160632" skip-condition-move-check="y" skip-condition-target-check="y"/>
          <result control-mode="classic" special-1="160632" special-ui-effect="event"/>
          <result control-mode="bns" special-1="160632" special-ui-effect="event"/>
        </decision>
        <decision>
          <condition skill="160631" skip-condition-move-check="y" skip-condition-target-check="y"/>
          <result control-mode="classic" special-1="160631" special-ui-effect="event"/>
          <result control-mode="bns" special-1="160631" special-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160630" skip-condition-move-check="y" skip-condition-target-check="y"/>
          <result control-mode="classic" special-1="160630" special-ui-effect="event"/>
          <result control-mode="bns" special-1="160630" special-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160640"/>
          <result control-mode="classic" skillbar-7="160640"/>
          <result control-mode="bns" skillbar-7="160640"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160580"/>
          <result control-mode="classic" skillbar-7="160580"/>
          <result control-mode="bns" skillbar-7="160580"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163340"/>
          <result context-3="163340" context-ui-effect="event" control-mode="classic"/>
          <result context-3="163340" context-ui-effect="event" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160070"/>
          <result context-3="160070" context-ui-effect="event" control-mode="classic"/>
          <result context-3="160070" context-ui-effect="event" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163454"/>
          <result cmd-key-right="163454" control-mode="classic" skillbar-ui-effect="combo"/>
          <result cmd-key-right="163454" control-mode="bns" skillbar-ui-effect="combo"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163464"/>
          <result cmd-key-left="163464" control-mode="classic" skillbar-ui-effect="combo"/>
          <result cmd-key-left="163464" control-mode="bns" skillbar-ui-effect="combo"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160884"/>
          <result cmd-key-right="163454" control-mode="classic" skillbar-ui-effect="combo"/>
          <result cmd-key-right="163454" control-mode="bns" skillbar-ui-effect="combo"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160894"/>
          <result cmd-key-left="163464" control-mode="classic" skillbar-ui-effect="combo"/>
          <result cmd-key-left="163464" control-mode="bns" skillbar-ui-effect="combo"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160504"/>
          <result cmd-key-right="160504" control-mode="classic" skillbar-ui-effect="combo"/>
          <result cmd-key-right="160504" control-mode="bns" skillbar-ui-effect="combo"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160514"/>
          <result cmd-key-left="160514" control-mode="classic" skillbar-ui-effect="combo"/>
          <result cmd-key-left="160514" control-mode="bns" skillbar-ui-effect="combo"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160720"/>
          <result context-ui-effect="combo" control-mode="classic" skillbar-2="160720"/>
          <result context-ui-effect="combo" control-mode="bns" skillbar-2="160720"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163210"/>
          <result control-mode="classic" skillbar-4="163210"/>
          <result control-mode="bns" skillbar-4="163210"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163105"/>
          <result control-mode="classic" skillbar-5="163105"/>
          <result control-mode="bns" skillbar-5="163105"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163090"/>
          <result control-mode="classic" skillbar-5="163090"/>
          <result control-mode="bns" skillbar-5="163090"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163129"/>
          <result context-3="163129" control-mode="classic"/>
          <result context-3="163129" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163128"/>
          <result context-3="163128" control-mode="classic"/>
          <result context-3="163128" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163127"/>
          <result context-3="163127" control-mode="classic"/>
          <result context-3="163127" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163126"/>
          <result context-3="163126" control-mode="classic"/>
          <result context-3="163126" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163125"/>
          <result context-3="163125" control-mode="classic"/>
          <result context-3="163125" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163124"/>
          <result context-3="163124" control-mode="classic"/>
          <result context-3="163124" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163123"/>
          <result context-3="163123" control-mode="classic"/>
          <result context-3="163123" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163122"/>
          <result context-3="163122" control-mode="classic"/>
          <result context-3="163122" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163121"/>
          <result context-3="163121" control-mode="classic"/>
          <result context-3="163121" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163120"/>
          <result context-3="163120" control-mode="classic"/>
          <result context-3="163120" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163023"/>
          <result context-2="163023" context-ui-effect="combo" control-mode="classic"/>
          <result context-2="163023" context-ui-effect="combo" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163022"/>
          <result context-2="163022" context-ui-effect="combo" control-mode="classic"/>
          <result context-2="163022" context-ui-effect="combo" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163023"/>
          <result context-ui-effect="combo" control-mode="classic" skillbar-7="163023"/>
          <result context-ui-effect="combo" control-mode="bns" skillbar-7="163023"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163022"/>
          <result context-ui-effect="combo" control-mode="classic" skillbar-7="163022"/>
          <result context-ui-effect="combo" control-mode="bns" skillbar-7="163022"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163021"/>
          <result context-ui-effect="combo" control-mode="classic" skillbar-7="163021"/>
          <result context-ui-effect="combo" control-mode="bns" skillbar-7="163021"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163033"/>
          <result context-2="163033" context-ui-effect="event" control-mode="classic"/>
          <result context-2="163033" context-ui-effect="event" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163032"/>
          <result context-2="163032" context-ui-effect="event" control-mode="classic"/>
          <result context-2="163032" context-ui-effect="event" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163031"/>
          <result context-2="163031" context-ui-effect="event" control-mode="classic"/>
          <result context-2="163031" context-ui-effect="event" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163033"/>
          <result context-ui-effect="event" control-mode="classic" skillbar-8="163033"/>
          <result context-ui-effect="event" control-mode="bns" skillbar-8="163033"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163032"/>
          <result context-ui-effect="event" control-mode="classic" skillbar-8="163032"/>
          <result context-ui-effect="event" control-mode="bns" skillbar-8="163032"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163031"/>
          <result context-ui-effect="event" control-mode="classic" skillbar-8="163031"/>
          <result context-ui-effect="event" control-mode="bns" skillbar-8="163031"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163011"/>
          <result context-2="163011" context-ui-effect="event" control-mode="classic"/>
          <result context-2="163011" context-ui-effect="event" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163010"/>
          <result context-2="163010" control-mode="classic"/>
          <result context-2="163010" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163402"/>
          <result context-2="163402" context-ui-effect="combo" control-mode="classic"/>
          <result context-2="163402" context-ui-effect="combo" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163401"/>
          <result context-2="163401" context-ui-effect="combo" control-mode="classic"/>
          <result context-2="163401" context-ui-effect="combo" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163400"/>
          <result context-2="163400" context-ui-effect="combo" control-mode="classic"/>
          <result context-2="163400" context-ui-effect="combo" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163002"/>
          <result context-2="163002" context-ui-effect="combo" control-mode="classic"/>
          <result context-2="163002" context-ui-effect="combo" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163001"/>
          <result context-2="163001" context-ui-effect="combo" control-mode="classic"/>
          <result context-2="163001" context-ui-effect="combo" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163000"/>
          <result context-2="163000" context-ui-effect="combo" control-mode="classic"/>
          <result context-2="163000" context-ui-effect="combo" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163360"/>
          <result context-1="163360" control-mode="classic"/>
          <result context-1="163360" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163272"/>
          <result context-2="163272" control-mode="classic"/>
          <result context-2="163272" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163271"/>
          <result context-2="163271" control-mode="classic"/>
          <result context-2="163271" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163270"/>
          <result context-2="163270" control-mode="classic"/>
          <result context-2="163270" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160170"/>
          <result control-mode="classic" skillbar-2="160170"/>
          <result control-mode="bns" skillbar-2="160170"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160260"/>
          <result context-2="160260" control-mode="classic"/>
          <result context-2="160260" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition field="job-style-only"/>
          <result cmd-key-double-left="65011" cmd-key-double-right="65012" cmd-key-down="160520" cmd-key-left="160500" cmd-key-right="160510" context-1="160260" context-2="160360" control-mode="classic" skillbar-1="160110" skillbar-2="160180" skillbar-3="160220" skillbar-4="160240" skillbar-5="160530" skillbar-6="160750" skillbar-7="160640" skillbar-8="160590" stance="160000"/>
          <result cmd-key-double-left="65011" cmd-key-double-right="65012" cmd-key-down="160520" cmd-key-left="160500" cmd-key-right="160510" context-1="160260" context-2="160360" control-mode="bns" skillbar-1="160110" skillbar-2="160180" skillbar-3="160220" skillbar-4="160240" skillbar-5="160530" skillbar-6="160750" skillbar-7="160640" skillbar-8="160590" stance="160000"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition field="job-style-only" job-style="base-2"/>
          <result cmd-key-double-left="65011" cmd-key-double-right="65012" cmd-key-down="160900" cmd-key-left="160880" cmd-key-right="160890" context-1="160260" context-2="160360" control-mode="classic" skillbar-1="160110" skillbar-2="160186" skillbar-3="160221" skillbar-4="160240" skillbar-5="160532" skillbar-6="160760" skillbar-7="160580" skillbar-8="160615" stance="160000"/>
          <result cmd-key-double-left="65011" cmd-key-double-right="65012" cmd-key-down="160900" cmd-key-left="160880" cmd-key-right="160890" context-1="160260" context-2="160360" control-mode="bns" skillbar-1="160110" skillbar-2="160186" skillbar-3="160221" skillbar-4="160240" skillbar-5="160532" skillbar-6="160760" skillbar-7="160580" skillbar-8="160615" stance="160000"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition field="job-style-only" job-style="advanced-1"/>
          <result cmd-key-double-left="65011" cmd-key-double-right="65012" cmd-key-down="160520" cmd-key-left="160500" cmd-key-right="160510" context-1="160260" context-2="160360" control-mode="classic" skillbar-1="160110" skillbar-2="160180" skillbar-3="160220" skillbar-4="160240" skillbar-5="160530" skillbar-6="160750" skillbar-7="160640" skillbar-8="160590" stance="160000"/>
          <result cmd-key-double-left="65011" cmd-key-double-right="65012" cmd-key-down="160520" cmd-key-left="160500" cmd-key-right="160510" context-1="160260" context-2="160360" control-mode="bns" skillbar-1="160110" skillbar-2="160180" skillbar-3="160220" skillbar-4="160240" skillbar-5="160530" skillbar-6="160750" skillbar-7="160640" skillbar-8="160590" stance="160000"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition field="job-style-only" job-style="advanced-2"/>
          <result cmd-key-double-left="65011" cmd-key-double-right="65012" cmd-key-down="160900" cmd-key-left="160880" cmd-key-right="160890" context-1="160260" context-2="160360" control-mode="classic" skillbar-1="160110" skillbar-2="160186" skillbar-3="160221" skillbar-4="160240" skillbar-5="160532" skillbar-6="160760" skillbar-7="160580" skillbar-8="160615" stance="160000"/>
          <result cmd-key-double-left="65011" cmd-key-double-right="65012" cmd-key-down="160900" cmd-key-left="160880" cmd-key-right="160890" context-1="160260" context-2="160360" control-mode="bns" skillbar-1="160110" skillbar-2="160186" skillbar-3="160221" skillbar-4="160240" skillbar-5="160532" skillbar-6="160760" skillbar-7="160580" skillbar-8="160615" stance="160000"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition field="job-style-only" job-style="advanced-3"/>
          <result cmd-key-double-left="65011" cmd-key-double-right="65012" cmd-key-down="160900" cmd-key-left="163450" cmd-key-right="163460" context-1="163270" context-2="163000" control-mode="classic" skillbar-1="160110" skillbar-2="163350" skillbar-3="163260" skillbar-4="163520" skillbar-5="163100" skillbar-6="163080" skillbar-7="163020" skillbar-8="163030" stance="163330"/>
          <result cmd-key-double-left="65011" cmd-key-double-right="65012" cmd-key-down="160900" cmd-key-left="163450" cmd-key-right="163460" context-1="163270" context-2="163000" control-mode="bns" skillbar-1="160110" skillbar-2="163350" skillbar-3="163260" skillbar-4="163520" skillbar-5="163100" skillbar-6="163080" skillbar-7="163020" skillbar-8="163030" stance="163330"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <result context-1="501" context-2="501" control-mode="classic" skillbar-1="501" skillbar-2="501" skillbar-3="501" skillbar-4="501" skillbar-5="501" skillbar-6="501" skillbar-7="501" skillbar-8="501" stance="501"/>
          <result context-1="501" context-2="501" control-mode="bns" skillbar-1="501" skillbar-2="501" skillbar-3="501" skillbar-4="501" skillbar-5="501" skillbar-6="501" skillbar-7="501" skillbar-8="501" stance="501"/>
        </decision>
      </layer>
    </stance>
    <stance stance="발도">
      <layer>
        <decision>
          <condition skill="66113"/>
          <result context-3="66113" control-mode="classic" skillbar-ui-effect="key-change"/>
          <result context-3="66113" control-mode="bns" skillbar-ui-effect="key-change"/>
        </decision>
        <decision>
          <condition skill="66114"/>
          <result context-3="66114" control-mode="classic" skillbar-ui-effect="key-change"/>
          <result context-3="66114" control-mode="bns" skillbar-ui-effect="key-change"/>
        </decision>
        <decision>
          <condition skill="65014"/>
          <result context-3="65014" control-mode="classic" skillbar-1="501" skillbar-2="501" skillbar-3="501" skillbar-4="501" skillbar-ui-effect="key-change"/>
          <result context-3="65014" control-mode="bns" skillbar-1="501" skillbar-2="501" skillbar-3="501" skillbar-4="501" skillbar-ui-effect="key-change"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="65013"/>
          <result context-3="65013" control-mode="classic" skillbar-1="501" skillbar-2="501" skillbar-3="501" skillbar-4="501" skillbar-ui-effect="key-change"/>
          <result context-3="65013" control-mode="bns" skillbar-1="501" skillbar-2="501" skillbar-3="501" skillbar-4="501" skillbar-ui-effect="key-change"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160061"/>
          <result context-2="160061" context-ui-effect="event" control-mode="classic"/>
          <result context-2="160061" context-ui-effect="event" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160060"/>
          <result context-2="160060" control-mode="classic"/>
          <result context-2="160060" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160051"/>
          <result context-2="160051" context-ui-effect="event" control-mode="classic"/>
          <result context-2="160051" context-ui-effect="event" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160050"/>
          <result context-2="160050" control-mode="classic"/>
          <result context-2="160050" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160400"/>
          <result context-3="160400" control-mode="classic"/>
          <result context-3="160400" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160680"/>
          <result context-3="160680" control-mode="classic"/>
          <result context-3="160680" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160300"/>
          <result context-2="160300" context-ui-effect="event" control-mode="classic"/>
          <result context-2="160300" context-ui-effect="event" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160270"/>
          <result context-2="160270" control-mode="classic"/>
          <result context-2="160270" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160020"/>
          <result context-3="160020" control-mode="classic"/>
          <result context-3="160020" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160470"/>
          <result context-2="160470" context-ui-effect="key-change" control-mode="classic"/>
          <result context-2="160470" context-ui-effect="key-change" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160322"/>
          <result context-1="160322" context-ui-effect="key-change" control-mode="classic"/>
          <result context-1="160322" context-ui-effect="key-change" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160323"/>
          <result context-1="160323" context-ui-effect="key-change" control-mode="classic"/>
          <result context-1="160323" context-ui-effect="key-change" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160320"/>
          <result context-1="160320" context-ui-effect="key-change" control-mode="classic"/>
          <result context-1="160320" context-ui-effect="key-change" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160321"/>
          <result context-1="160321" context-ui-effect="key-change" control-mode="classic"/>
          <result context-1="160321" context-ui-effect="key-change" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163105"/>
          <result control-mode="classic" skillbar-5="163105"/>
          <result control-mode="bns" skillbar-5="163105"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163091"/>
          <result control-mode="classic" skillbar-5="163091"/>
          <result control-mode="bns" skillbar-5="163091"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164100"/>
          <result cmd-key-right="164100" control-mode="classic"/>
          <result cmd-key-right="164100" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160340"/>
          <result context-1="160340" context-2="160490" context-ui-effect="event" control-mode="classic"/>
          <result context-1="160340" context-2="160490" context-ui-effect="event" control-mode="bns"/>
        </decision>
        <decision>
          <condition skill="160490"/>
          <result context-1="160340" context-2="160490" context-ui-effect="event" control-mode="classic"/>
          <result context-1="160340" context-2="160490" context-ui-effect="event" control-mode="bns"/>
        </decision>
        <decision>
          <condition skill="163290"/>
          <result context-1="163290" context-2="163310" context-ui-effect="event" control-mode="classic"/>
          <result context-1="163290" context-2="163310" context-ui-effect="event" control-mode="bns"/>
        </decision>
        <decision>
          <condition skill="163310"/>
          <result context-1="163290" context-2="163310" context-ui-effect="event" control-mode="classic"/>
          <result context-1="163290" context-2="163310" context-ui-effect="event" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160330"/>
          <result context-1="160330" context-2="160480" context-ui-effect="event" control-mode="classic"/>
          <result context-1="160330" context-2="160480" context-ui-effect="event" control-mode="bns"/>
        </decision>
        <decision>
          <condition skill="160480"/>
          <result context-1="160330" context-2="160480" context-ui-effect="event" control-mode="classic"/>
          <result context-1="160330" context-2="160480" context-ui-effect="event" control-mode="bns"/>
        </decision>
        <decision>
          <condition skill="163300"/>
          <result context-1="163320" context-2="163300" context-ui-effect="event" control-mode="classic"/>
          <result context-1="163320" context-2="163300" context-ui-effect="event" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160350"/>
          <result context-1="160350" context-ui-effect="event" control-mode="classic"/>
          <result context-1="160350" context-ui-effect="event" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160671"/>
          <result context-ui-effect="event" control-mode="classic" skillbar-8="160671"/>
          <result context-ui-effect="event" control-mode="bns" skillbar-8="160671"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160670"/>
          <result control-mode="classic" skillbar-8="160670"/>
          <result control-mode="bns" skillbar-8="160670"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160610"/>
          <result control-mode="classic" skillbar-8="160610"/>
          <result control-mode="bns" skillbar-8="160610"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="27500"/>
          <result context-1="27500" context-ui-effect="event" control-mode="classic"/>
          <result context-1="27500" context-ui-effect="event" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160760"/>
          <result control-mode="classic" skillbar-6="160760"/>
          <result control-mode="bns" skillbar-6="160760"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164100"/>
          <result control-mode="classic" Skillbar-1="164100"/>
          <result control-mode="bns" Skillbar-1="164100"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160121"/>
          <result control-mode="classic" skillbar-1="160121"/>
          <result control-mode="bns" skillbar-1="160121"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160120"/>
          <result control-mode="classic" skillbar-1="160120"/>
          <result control-mode="bns" skillbar-1="160120"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="66204" skip-condition-move-check="y" skip-condition-target-check="y"/>
          <result control-mode="classic" special-2="66204" special-ui-effect="event"/>
          <result control-mode="bns" special-2="66204" special-ui-effect="event"/>
        </decision>
        <decision>
          <condition skill="66203" skip-condition-move-check="y" skip-condition-target-check="y"/>
          <result control-mode="classic" special-2="66203" special-ui-effect="event"/>
          <result control-mode="bns" special-2="66203" special-ui-effect="event"/>
        </decision>
        <decision>
          <condition skill="66202" skip-condition-move-check="y" skip-condition-target-check="y"/>
          <result control-mode="classic" special-2="66202" special-ui-effect="event"/>
          <result control-mode="bns" special-2="66202" special-ui-effect="event"/>
        </decision>
        <decision>
          <condition skill="66201" skip-condition-move-check="y" skip-condition-target-check="y"/>
          <result control-mode="classic" special-2="66201" special-ui-effect="event"/>
          <result control-mode="bns" special-2="66201" special-ui-effect="event"/>
        </decision>
        <decision>
          <condition skill="66200" skip-condition-move-check="y" skip-condition-target-check="y"/>
          <result control-mode="classic" special-2="66200" special-ui-effect="event"/>
          <result control-mode="bns" special-2="66200" special-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160635" skip-condition-move-check="y" skip-condition-target-check="y"/>
          <result control-mode="classic" special-2="160635" special-ui-effect="event"/>
          <result control-mode="bns" special-2="160635" special-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160241"/>
          <result control-mode="classic" skillbar-4="160241"/>
          <result control-mode="bns" skillbar-4="160241"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160242"/>
          <result control-mode="classic" skillbar-4="160242"/>
          <result control-mode="bns" skillbar-4="160242"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160240"/>
          <result control-mode="classic" skillbar-4="160240"/>
          <result control-mode="bns" skillbar-4="160240"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160244"/>
          <result control-mode="classic" skillbar-4="160244"/>
          <result control-mode="bns" skillbar-4="160244"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160245"/>
          <result control-mode="classic" skillbar-4="160245"/>
          <result control-mode="bns" skillbar-4="160245"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160243"/>
          <result control-mode="classic" skillbar-4="160243"/>
          <result control-mode="bns" skillbar-4="160243"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163521"/>
          <result control-mode="classic" skillbar-4="163521"/>
          <result control-mode="bns" skillbar-4="163521"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163522"/>
          <result control-mode="classic" skillbar-4="163522"/>
          <result control-mode="bns" skillbar-4="163522"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163520"/>
          <result control-mode="classic" skillbar-4="163520"/>
          <result control-mode="bns" skillbar-4="163520"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163524"/>
          <result control-mode="classic" skillbar-4="163524"/>
          <result control-mode="bns" skillbar-4="163524"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163525"/>
          <result control-mode="classic" skillbar-4="163525"/>
          <result control-mode="bns" skillbar-4="163525"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163523"/>
          <result control-mode="classic" skillbar-4="163523"/>
          <result control-mode="bns" skillbar-4="163523"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163470"/>
          <result control-mode="classic" skillbar-5="163470"/>
          <result control-mode="bns" skillbar-5="163470"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160535"/>
          <result control-mode="classic" skillbar-5="160535"/>
          <result control-mode="bns" skillbar-5="160535"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160531"/>
          <result control-mode="classic" skillbar-5="160531"/>
          <result control-mode="bns" skillbar-5="160531"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="66304" skip-condition-move-check="y" skip-condition-target-check="y"/>
          <result control-mode="classic" special-1="66304" special-ui-effect="event"/>
          <result control-mode="bns" special-1="66304" special-ui-effect="event"/>
        </decision>
        <decision>
          <condition skill="66303" skip-condition-move-check="y" skip-condition-target-check="y"/>
          <result control-mode="classic" special-1="66303" special-ui-effect="event"/>
          <result control-mode="bns" special-1="66303" special-ui-effect="event"/>
        </decision>
        <decision>
          <condition skill="66302" skip-condition-move-check="y" skip-condition-target-check="y"/>
          <result control-mode="classic" special-1="66302" special-ui-effect="event"/>
          <result control-mode="bns" special-1="66302" special-ui-effect="event"/>
        </decision>
        <decision>
          <condition skill="66301" skip-condition-move-check="y" skip-condition-target-check="y"/>
          <result control-mode="classic" special-1="66301" special-ui-effect="event"/>
          <result control-mode="bns" special-1="66301" special-ui-effect="event"/>
        </decision>
        <decision>
          <condition skill="66300" skip-condition-move-check="y" skip-condition-target-check="y"/>
          <result control-mode="classic" special-1="66300" special-ui-effect="event"/>
          <result control-mode="bns" special-1="66300" special-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160632" skip-condition-move-check="y" skip-condition-target-check="y"/>
          <result control-mode="classic" special-1="160632" special-ui-effect="event"/>
          <result control-mode="bns" special-1="160632" special-ui-effect="event"/>
        </decision>
        <decision>
          <condition skill="160631" skip-condition-move-check="y" skip-condition-target-check="y"/>
          <result control-mode="classic" special-1="160631" special-ui-effect="event"/>
          <result control-mode="bns" special-1="160631" special-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160630" skip-condition-move-check="y" skip-condition-target-check="y"/>
          <result control-mode="classic" special-1="160630" special-ui-effect="event"/>
          <result control-mode="bns" special-1="160630" special-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition combination-key-command-2="move-forward" skill="160430"/>
          <result control-mode="classic" skillbar-7="160430"/>
          <result control-mode="bns" skillbar-7="160430"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160580"/>
          <result control-mode="classic" skillbar-7="160580"/>
          <result control-mode="bns" skillbar-7="160580"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition combination-key-command-2="move-forward" skill="160420"/>
          <result context-1="160420" control-mode="classic"/>
          <result context-1="160420" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160415"/>
          <result context-1="160415" control-mode="classic"/>
          <result context-1="160415" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition field="job-style-only"/>
          <result context-2="160410" control-mode="classic"/>
          <result context-2="160410" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition field="job-style-only" job-style="advanced-1"/>
          <result context-2="160410" control-mode="classic"/>
          <result context-2="160410" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160422"/>
          <result context-2="160422" control-mode="classic"/>
          <result context-2="160422" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160505"/>
          <result cmd-key-right="160505" control-mode="classic" skillbar-ui-effect="combo"/>
          <result cmd-key-right="160505" control-mode="bns" skillbar-ui-effect="combo"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160515"/>
          <result cmd-key-left="160515" control-mode="classic" skillbar-ui-effect="combo"/>
          <result cmd-key-left="160515" control-mode="bns" skillbar-ui-effect="combo"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160885"/>
          <result cmd-key-right="160885" control-mode="classic" skillbar-ui-effect="combo"/>
          <result cmd-key-right="160885" control-mode="bns" skillbar-ui-effect="combo"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160895"/>
          <result cmd-key-left="160895" control-mode="classic" skillbar-ui-effect="combo"/>
          <result cmd-key-left="160895" control-mode="bns" skillbar-ui-effect="combo"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="27276"/>
          <result cmd-key-right="27276" control-mode="classic" skillbar-ui-effect="combo"/>
          <result cmd-key-right="27276" control-mode="bns" skillbar-ui-effect="combo"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="27277"/>
          <result cmd-key-left="27277" control-mode="classic" skillbar-ui-effect="combo"/>
          <result cmd-key-left="27277" control-mode="bns" skillbar-ui-effect="combo"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160171"/>
          <result control-mode="classic" skillbar-2="160171"/>
          <result control-mode="bns" skillbar-2="160171"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160185"/>
          <result control-mode="classic" skillbar-2="160185"/>
          <result control-mode="bns" skillbar-2="160185"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160183"/>
          <result control-mode="classic" skillbar-2="160183"/>
          <result control-mode="bns" skillbar-2="160183"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160182"/>
          <result control-mode="classic" skillbar-2="160182"/>
          <result control-mode="bns" skillbar-2="160182"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160189"/>
          <result control-mode="classic" skillbar-2="160189"/>
          <result control-mode="bns" skillbar-2="160189"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160188"/>
          <result control-mode="classic" skillbar-2="160188"/>
          <result control-mode="bns" skillbar-2="160188"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="160187"/>
          <result control-mode="classic" skillbar-2="160187"/>
          <result control-mode="bns" skillbar-2="160187"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163353"/>
          <result control-mode="classic" skillbar-2="163353"/>
          <result control-mode="bns" skillbar-2="163353"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163352"/>
          <result control-mode="classic" skillbar-2="163352"/>
          <result control-mode="bns" skillbar-2="163352"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163351"/>
          <result control-mode="classic" skillbar-2="163351"/>
          <result control-mode="bns" skillbar-2="163351"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163052"/>
          <result context-2="163052" control-mode="classic"/>
          <result context-2="163052" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163051"/>
          <result context-2="163051" control-mode="classic"/>
          <result context-2="163051" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163050"/>
          <result context-2="163050" control-mode="classic"/>
          <result context-2="163050" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163443"/>
          <result context-2="163443" control-mode="classic" skillbar-ui-effect="combo"/>
          <result context-2="163443" control-mode="bns" skillbar-ui-effect="combo"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163442"/>
          <result context-2="163442" control-mode="classic" skillbar-ui-effect="combo"/>
          <result context-2="163442" control-mode="bns" skillbar-ui-effect="combo"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163440"/>
          <result context-2="163440" control-mode="classic" skillbar-ui-effect="combo"/>
          <result context-2="163440" control-mode="bns" skillbar-ui-effect="combo"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163043"/>
          <result context-2="163043" control-mode="classic" skillbar-ui-effect="combo"/>
          <result context-2="163043" control-mode="bns" skillbar-ui-effect="combo"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163042"/>
          <result context-2="163042" control-mode="classic" skillbar-ui-effect="combo"/>
          <result context-2="163042" control-mode="bns" skillbar-ui-effect="combo"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163040"/>
          <result context-2="163040" control-mode="classic" skillbar-ui-effect="combo"/>
          <result context-2="163040" control-mode="bns" skillbar-ui-effect="combo"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163060"/>
          <result context-2="163060" control-mode="classic" skillbar-ui-effect="combo"/>
          <result context-2="163060" control-mode="bns" skillbar-ui-effect="combo"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="163510"/>
          <result context-1="163510" context-ui-effect="event" control-mode="classic"/>
          <result context-1="163510" context-ui-effect="event" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition field="job-style-only"/>
          <result cmd-key-double-left="65011" cmd-key-double-right="65012" cmd-key-down="160520" cmd-key-left="160500" cmd-key-right="160510" context-1="160270" context-2="160360" control-mode="classic" skillbar-1="160110" skillbar-2="160182" skillbar-3="160220" skillbar-4="160240" skillbar-5="160530" skillbar-6="160711" skillbar-7="160640" skillbar-8="160590" stance="160000"/>
          <result cmd-key-double-left="65011" cmd-key-double-right="65012" cmd-key-down="160520" cmd-key-left="160500" cmd-key-right="160510" context-1="160270" context-2="160360" control-mode="bns" skillbar-1="160110" skillbar-2="160182" skillbar-3="160220" skillbar-4="160240" skillbar-5="160530" skillbar-6="160711" skillbar-7="160640" skillbar-8="160590" stance="160000"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition field="job-style-only" job-style="base-2"/>
          <result cmd-key-double-left="65011" cmd-key-double-right="65012" cmd-key-down="160900" cmd-key-left="160880" cmd-key-right="160890" context-1="160270" context-2="160360" control-mode="classic" skillbar-1="160110" skillbar-2="160187" skillbar-3="160221" skillbar-4="160240" skillbar-5="160532" skillbar-6="160760" skillbar-7="160580" skillbar-8="160610" stance="160000"/>
          <result cmd-key-double-left="65011" cmd-key-double-right="65012" cmd-key-down="160900" cmd-key-left="160880" cmd-key-right="160890" context-1="160270" context-2="160360" control-mode="bns" skillbar-1="160110" skillbar-2="160187" skillbar-3="160221" skillbar-4="160240" skillbar-5="160532" skillbar-6="160760" skillbar-7="160580" skillbar-8="160610" stance="160000"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition field="job-style-only" job-style="advanced-1"/>
          <result cmd-key-double-left="65011" cmd-key-double-right="65012" cmd-key-down="160520" cmd-key-left="160500" cmd-key-right="160510" context-1="160270" context-2="160360" control-mode="classic" skillbar-1="160110" skillbar-2="160182" skillbar-3="160220" skillbar-4="160240" skillbar-5="160530" skillbar-6="160711" skillbar-7="160640" skillbar-8="160590" stance="160000"/>
          <result cmd-key-double-left="65011" cmd-key-double-right="65012" cmd-key-down="160520" cmd-key-left="160500" cmd-key-right="160510" context-1="160270" context-2="160360" control-mode="bns" skillbar-1="160110" skillbar-2="160182" skillbar-3="160220" skillbar-4="160240" skillbar-5="160530" skillbar-6="160711" skillbar-7="160640" skillbar-8="160590" stance="160000"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition field="job-style-only" job-style="advanced-2"/>
          <result cmd-key-double-left="65011" cmd-key-double-right="65012" cmd-key-down="160900" cmd-key-left="160880" cmd-key-right="160890" context-1="160270" context-2="160360" control-mode="classic" skillbar-1="160110" skillbar-2="160187" skillbar-3="160221" skillbar-4="160240" skillbar-5="160532" skillbar-6="160760" skillbar-7="160580" skillbar-8="160610" stance="160000"/>
          <result cmd-key-double-left="65011" cmd-key-double-right="65012" cmd-key-down="160900" cmd-key-left="160880" cmd-key-right="160890" context-1="160270" context-2="160360" control-mode="bns" skillbar-1="160110" skillbar-2="160187" skillbar-3="160221" skillbar-4="160240" skillbar-5="160532" skillbar-6="160760" skillbar-7="160580" skillbar-8="160610" stance="160000"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition field="job-style-only" job-style="advanced-3"/>
          <result cmd-key-double-left="65011" cmd-key-double-right="65012" cmd-key-down="160900" cmd-key-left="163450" cmd-key-right="163460" context-1="163361" control-mode="classic" skillbar-1="160110" skillbar-2="163351" skillbar-3="163260" skillbar-4="163520" skillbar-5="163100" skillbar-6="163370" skillbar-7="163060" skillbar-8="163070" stance="163330"/>
          <result cmd-key-double-left="65011" cmd-key-double-right="65012" cmd-key-down="160900" cmd-key-left="163450" cmd-key-right="163460" context-1="163361" control-mode="bns" skillbar-1="160110" skillbar-2="163351" skillbar-3="163260" skillbar-4="163520" skillbar-5="163100" skillbar-6="163370" skillbar-7="163060" skillbar-8="163070" stance="163330"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <result context-1="501" context-2="501" control-mode="classic" skillbar-1="501" skillbar-2="501" skillbar-3="501" skillbar-4="501" skillbar-5="501" skillbar-6="501" skillbar-7="501" skillbar-8="501" stance="501"/>
          <result context-1="501" context-2="501" control-mode="bns" skillbar-1="501" skillbar-2="501" skillbar-3="501" skillbar-4="501" skillbar-5="501" skillbar-6="501" skillbar-7="501" skillbar-8="501" stance="501"/>
        </decision>
      </layer>
    </stance>
  </contextscript>
  <contextscript alias="SwordMaster_ContextSimpleMode_G1_Var_2" context-simple-mode="y" job="소환수-루키" race="악귀">
    <stance stance="소환수-command-1">
      <layer>
        <decision>
          <condition skill="164130"/>
          <result control-mode="classic" skillbar-7="164130" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-7="164130" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164129"/>
          <result control-mode="classic" skillbar-7="164129" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-7="164129" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164128"/>
          <result control-mode="classic" skillbar-7="164128" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-7="164128" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164127"/>
          <result control-mode="classic" skillbar-7="164127" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-7="164127" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164126"/>
          <result control-mode="classic" skillbar-7="164126" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-7="164126" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164125"/>
          <result control-mode="classic" skillbar-7="164125" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-7="164125" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164124"/>
          <result control-mode="classic" skillbar-7="164124" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-7="164124" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164123"/>
          <result control-mode="classic" skillbar-7="164123" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-7="164123" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164122"/>
          <result control-mode="classic" skillbar-7="164122" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-7="164122" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164121"/>
          <result control-mode="classic" skillbar-7="164121" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-7="164121" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164091"/>
          <result context-1="164091" control-mode="classic" skillbar-ui-effect="event"/>
          <result context-1="164091" control-mode="bns" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164021"/>
          <result control-mode="classic" skillbar-2="164021" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-2="164021" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164061"/>
          <result control-mode="classic" skillbar-2="164061" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-2="164061" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164071"/>
          <result context-1="164071" control-mode="classic"/>
          <result context-1="164071" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164040"/>
          <result control-mode="classic" skillbar-3="164040"/>
          <result control-mode="bns" skillbar-3="164040"/>
        </decision>
      </layer>
    </stance>
  </contextscript>
  <contextscript alias="SwordMaster_ContextSimpleMode_G1_Var_3" context-simple-mode="y" job="소환수-striker" race="악귀">
    <stance stance="소환수-command-1">
      <layer>
        <decision>
          <condition skill="164130"/>
          <result control-mode="classic" skillbar-7="164130" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-7="164130" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164129"/>
          <result control-mode="classic" skillbar-7="164129" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-7="164129" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164128"/>
          <result control-mode="classic" skillbar-7="164128" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-7="164128" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164127"/>
          <result control-mode="classic" skillbar-7="164127" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-7="164127" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164126"/>
          <result control-mode="classic" skillbar-7="164126" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-7="164126" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164125"/>
          <result control-mode="classic" skillbar-7="164125" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-7="164125" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164124"/>
          <result control-mode="classic" skillbar-7="164124" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-7="164124" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164123"/>
          <result control-mode="classic" skillbar-7="164123" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-7="164123" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164122"/>
          <result control-mode="classic" skillbar-7="164122" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-7="164122" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164121"/>
          <result control-mode="classic" skillbar-7="164121" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-7="164121" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164091"/>
          <result context-1="164091" control-mode="classic" skillbar-ui-effect="event"/>
          <result context-1="164091" control-mode="bns" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164021"/>
          <result control-mode="classic" skillbar-2="164021" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-2="164021" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164061"/>
          <result control-mode="classic" skillbar-2="164061" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-2="164061" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164071"/>
          <result context-1="164071" control-mode="classic"/>
          <result context-1="164071" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164040"/>
          <result control-mode="classic" skillbar-3="164040"/>
          <result control-mode="bns" skillbar-3="164040"/>
        </decision>
      </layer>
    </stance>
  </contextscript>
  <contextscript alias="SwordMaster_ContextSimpleMode_G1_Var_4" context-simple-mode="y" job="소환수-defender" race="악귀">
    <stance stance="소환수-command-1">
      <layer>
        <decision>
          <condition skill="164130"/>
          <result control-mode="classic" skillbar-7="164130" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-7="164130" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164129"/>
          <result control-mode="classic" skillbar-7="164129" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-7="164129" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164128"/>
          <result control-mode="classic" skillbar-7="164128" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-7="164128" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164127"/>
          <result control-mode="classic" skillbar-7="164127" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-7="164127" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164126"/>
          <result control-mode="classic" skillbar-7="164126" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-7="164126" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164125"/>
          <result control-mode="classic" skillbar-7="164125" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-7="164125" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164124"/>
          <result control-mode="classic" skillbar-7="164124" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-7="164124" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164123"/>
          <result control-mode="classic" skillbar-7="164123" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-7="164123" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164122"/>
          <result control-mode="classic" skillbar-7="164122" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-7="164122" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164121"/>
          <result control-mode="classic" skillbar-7="164121" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-7="164121" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164091"/>
          <result context-1="164091" control-mode="classic" skillbar-ui-effect="event"/>
          <result context-1="164091" control-mode="bns" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164021"/>
          <result control-mode="classic" skillbar-2="164021" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-2="164021" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164061"/>
          <result control-mode="classic" skillbar-2="164061" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-2="164061" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164071"/>
          <result context-1="164071" control-mode="classic"/>
          <result context-1="164071" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164040"/>
          <result control-mode="classic" skillbar-3="164040"/>
          <result control-mode="bns" skillbar-3="164040"/>
        </decision>
      </layer>
    </stance>
  </contextscript>
  <contextscript alias="SwordMaster_ContextSimpleMode_G1_Var_5" context-simple-mode="y" job="소환수-controller" race="악귀">
    <stance stance="소환수-command-1">
      <layer>
        <decision>
          <condition skill="164130"/>
          <result control-mode="classic" skillbar-7="164130" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-7="164130" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164129"/>
          <result control-mode="classic" skillbar-7="164129" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-7="164129" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164128"/>
          <result control-mode="classic" skillbar-7="164128" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-7="164128" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164127"/>
          <result control-mode="classic" skillbar-7="164127" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-7="164127" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164126"/>
          <result control-mode="classic" skillbar-7="164126" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-7="164126" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164125"/>
          <result control-mode="classic" skillbar-7="164125" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-7="164125" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164124"/>
          <result control-mode="classic" skillbar-7="164124" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-7="164124" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164123"/>
          <result control-mode="classic" skillbar-7="164123" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-7="164123" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164122"/>
          <result control-mode="classic" skillbar-7="164122" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-7="164122" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164121"/>
          <result control-mode="classic" skillbar-7="164121" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-7="164121" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164091"/>
          <result context-1="164091" control-mode="classic" skillbar-ui-effect="event"/>
          <result context-1="164091" control-mode="bns" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164021"/>
          <result control-mode="classic" skillbar-2="164021" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-2="164021" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164061"/>
          <result control-mode="classic" skillbar-2="164061" skillbar-ui-effect="event"/>
          <result control-mode="bns" skillbar-2="164061" skillbar-ui-effect="event"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164071"/>
          <result context-1="164071" control-mode="classic"/>
          <result context-1="164071" control-mode="bns"/>
        </decision>
      </layer>
      <layer>
        <decision>
          <condition skill="164040"/>
          <result control-mode="classic" skillbar-3="164040"/>
          <result control-mode="bns" skillbar-3="164040"/>
        </decision>
      </layer>
    </stance>
  </contextscript>
</table>
