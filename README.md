<?xml version="1.1" encoding="UTF-8" standalone="yes" ?>
<program>
  <header>
    <applicationBuildName></applicationBuildName>
    <applicationBuildNumber>0</applicationBuildNumber>
    <applicationBuildType>signedRelease</applicationBuildType>
    <applicationName>Pocket Code</applicationName>
    <applicationVersion>1.0.1</applicationVersion>
    <catrobatLanguageVersion>1.01</catrobatLanguageVersion>
    <dateTimeUpload></dateTimeUpload>
    <description></description>
    <deviceName>moto e13</deviceName>
    <isCastProject>false</isCastProject>
    <landscapeMode>true</landscapeMode>
    <listeningLanguageTag></listeningLanguageTag>
    <mediaLicense></mediaLicense>
    <notesAndCredits></notesAndCredits>
    <platform>Android</platform>
    <platformVersion>33</platformVersion>
    <programLicense></programLicense>
    <programName>DBZ Rivalsz</programName>
    <remixOf></remixOf>
    <scenesEnabled>true</scenesEnabled>
    <screenHeight>1179</screenHeight>
    <screenMode>STRETCH</screenMode>
    <screenWidth>2419</screenWidth>
    <tags></tags>
    <url></url>
    <userHandle></userHandle>
  </header>
  <settings/>
  <scenes>
    <scene>
      <name>Cena</name>
      <objectList>
        <object type="Sprite" name="Fundo">
          <lookList>
            <look fileName="imagwwwes.jpeg" name="imagwwwes">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetSizeToBrick">
                  <brickId>82e93777-3ccc-48f4-b6b6-1edbfb7bd1c5</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>350</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>ac830b85-e0a2-445b-aac2-01cab6cefcdb</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Start">
          <lookList>
            <look fileName="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d.png" name="Start">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>683198ec-706e-41a9-b9be-5417646773e1</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>7</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>116</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>efa90d1f-6e75-49e1-9aee-1f967b9c2640</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>700</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>c9150ebe-1cc6-46b8-977a-cbfcc119c05d</scriptId>
            </script>
            <script type="WhenScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetSizeToBrick">
                  <brickId>c5e14a53-207f-4b63-b224-88832d86c30e</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>600</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="WaitBrick">
                  <brickId>542704f9-afc9-4ab5-b6b9-47437ca85e4e</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.1</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>b632582a-e2f9-4c53-ad67-88cff92b535f</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>700</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="WaitBrick">
                  <brickId>de2c5d0c-04a6-4cc8-997f-7ad0f5ee22f6</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.3</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SceneStartBrick">
                  <brickId>269d6c80-edbc-4482-be82-7bb872769ef2</brickId>
                  <commentedOut>false</commentedOut>
                  <sceneToStart>Escolha De Personagem</sceneToStart>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>b32ef0d7-d495-4f93-8031-802311c63179</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Título ">
          <lookList>
            <look fileName="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d_#0.png" name="Título ">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetSizeToBrick">
                  <brickId>a555460f-1a25-4657-a26a-f3f5a4cb3334</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>700</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="PlaceAtBrick">
                  <brickId>bdbb4cbd-82e6-4d46-8dc2-0597633bb5c0</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>200</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="PlaceAtBrick">
                  <brickId>ed213eee-a59e-4a9a-8dc2-13378a77cd63</brickId>
                  <commentedOut>true</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>100</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>200</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="ForeverBrick">
                  <brickId>e4a3793b-84da-4bd3-bc3f-e48f7dbd21fd</brickId>
                  <commentedOut>false</commentedOut>
                  <loopBricks>
                    <brick type="GlideToBrick">
                      <brickId>d28ca979-d200-4f31-829d-65851f9a3634</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="X_DESTINATION">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>0</value>
                        </formula>
                        <formula category="DURATION_IN_SECONDS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>1.0</value>
                        </formula>
                        <formula category="Y_DESTINATION">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>200</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="GlideToBrick">
                      <brickId>02986585-6767-4929-86c1-604aae075e84</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="X_DESTINATION">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>0</value>
                        </formula>
                        <formula category="DURATION_IN_SECONDS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>1.0</value>
                        </formula>
                        <formula category="Y_DESTINATION">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>190</value>
                        </formula>
                      </formulaList>
                    </brick>
                  </loopBricks>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>22b9f9b2-5f49-4767-990a-ef082ab8ee0c</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
      </objectList>
    </scene>
    <scene>
      <name>Escolha De Personagem</name>
      <objectList>
        <object type="Sprite" name="Fundo">
          <lookList>
            <look fileName="imnjjhages.jpeg" name="imnjjhages">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetSizeToBrick">
                  <brickId>7debf7b1-5975-4753-b529-dd3b36ed4114</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>355</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>5d1be98a-a06c-42fd-adb0-f9923c9c8daf</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Face_Goku">
          <lookList>
            <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd.png" name="Face_Goku">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>9d8fd3f0-e360-4cb1-af2f-1d2022cf5db7</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>766</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>300</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>d5763658-177e-46fc-b3c1-97514b8228c6</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>200</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>d231c5a4-034b-4238-bee2-c0441e7ba687</scriptId>
            </script>
            <script type="WhenScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetBrightnessBrick">
                  <brickId>a4d33fd3-da49-4d0f-bfdb-17e30d60503f</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="BRIGHTNESS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>100</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="ChangeVariableBrick">
                  <brickId>197af7bd-4029-4bd3-99fe-0e5608696880</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="VARIABLE_CHANGE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>1.0</value>
                    </formula>
                  </formulaList>
                  <userVariable type="UserVariable" serialization="custom">
                    <userVariable>
                      <default>
                        <initialIndex>0</initialIndex>
                        <deviceValueKey>2454597e-424f-43c5-bf93-5e9e883772a8</deviceValueKey>
                        <name>Goku</name>
                      </default>
                    </userVariable>
                  </userVariable>
                </brick>
                <brick type="ChangeVariableBrick">
                  <brickId>dfdf0f9b-719c-47dc-a890-91ead843a768</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="VARIABLE_CHANGE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>1.0</value>
                    </formula>
                  </formulaList>
                  <userVariable type="UserVariable" serialization="custom">
                    <userVariable>
                      <default>
                        <initialIndex>1</initialIndex>
                        <deviceValueKey>f1a3e40c-0e6d-43ff-9574-8340d3a62910</deviceValueKey>
                        <name>Jogar</name>
                      </default>
                    </userVariable>
                  </userVariable>
                </brick>
                <brick type="IfThenLogicBeginBrick">
                  <brickId>2cfa97ae-0e23-446c-94f0-4bba93d20fa1</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="IF_CONDITION">
                      <additionalChildren/>
                      <leftChild>
                        <additionalChildren/>
                        <type>USER_VARIABLE</type>
                        <value>Goku</value>
                      </leftChild>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>2</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>EQUAL</value>
                    </formula>
                  </formulaList>
                  <ifBranchBricks>
                    <brick type="ChangeVariableBrick">
                      <brickId>130913a2-c897-43fa-a7a3-bb415761e4e3</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="VARIABLE_CHANGE">
                          <additionalChildren/>
                          <rightChild>
                            <additionalChildren/>
                            <type>NUMBER</type>
                            <value>2</value>
                          </rightChild>
                          <type>OPERATOR</type>
                          <value>MINUS</value>
                        </formula>
                      </formulaList>
                      <userVariable reference="../../../../brick[2]/userVariable"/>
                    </brick>
                    <brick type="ChangeVariableBrick">
                      <brickId>84ead73e-4e26-4dab-9403-83978bd7371a</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="VARIABLE_CHANGE">
                          <additionalChildren/>
                          <rightChild>
                            <additionalChildren/>
                            <type>NUMBER</type>
                            <value>2</value>
                          </rightChild>
                          <type>OPERATOR</type>
                          <value>MINUS</value>
                        </formula>
                      </formulaList>
                      <userVariable reference="../../../../brick[3]/userVariable"/>
                    </brick>
                    <brick type="SetBrightnessBrick">
                      <brickId>5bc8d7c3-f007-47c8-8548-4c4af4844147</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="BRIGHTNESS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>50</value>
                        </formula>
                      </formulaList>
                    </brick>
                  </ifBranchBricks>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>25a9feab-4ae8-410d-8997-f76b3bd07ccb</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Face_Vegeta">
          <lookList>
            <look fileName="vegeta___ultimate_lsw_sheet_by_qsab101_dbzqwt5.png" name="Face_Vegeta">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>4018ef24-8f95-4202-b650-6eb7a90a72cc</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>728</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>300</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>3769e8f5-45fc-47db-a50f-8f12d5acae03</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>99</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>d8800edd-270f-4219-b377-ee3860ca86f3</scriptId>
            </script>
            <script type="WhenScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetBrightnessBrick">
                  <brickId>f4171911-9bb4-4ee7-bf61-9eec359a2a38</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="BRIGHTNESS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>100</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="ChangeVariableBrick">
                  <brickId>3292380f-321b-4727-84e5-9de2f5d0cd90</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="VARIABLE_CHANGE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>1.0</value>
                    </formula>
                  </formulaList>
                  <userVariable type="UserVariable" serialization="custom">
                    <userVariable>
                      <default>
                        <initialIndex>2</initialIndex>
                        <deviceValueKey>a5325a70-e696-45c7-9d89-2aa98b4f394e</deviceValueKey>
                        <name>Vegeta</name>
                      </default>
                    </userVariable>
                  </userVariable>
                </brick>
                <brick type="ChangeVariableBrick">
                  <brickId>f7b5cca3-48b5-4fcb-af57-2ac3036f808e</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="VARIABLE_CHANGE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>1.0</value>
                    </formula>
                  </formulaList>
                  <userVariable reference="../../../../../../object[2]/scriptList/script[2]/brickList/brick[3]/userVariable"/>
                </brick>
                <brick type="IfThenLogicBeginBrick">
                  <brickId>46b7ea4a-86bc-41e1-b939-408568a33968</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="IF_CONDITION">
                      <additionalChildren/>
                      <leftChild>
                        <additionalChildren/>
                        <type>USER_VARIABLE</type>
                        <value>Vegeta</value>
                      </leftChild>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>2</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>EQUAL</value>
                    </formula>
                  </formulaList>
                  <ifBranchBricks>
                    <brick type="ChangeVariableBrick">
                      <brickId>a5ab85a1-3358-40a0-8011-384ca08000ee</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="VARIABLE_CHANGE">
                          <additionalChildren/>
                          <rightChild>
                            <additionalChildren/>
                            <type>NUMBER</type>
                            <value>2</value>
                          </rightChild>
                          <type>OPERATOR</type>
                          <value>MINUS</value>
                        </formula>
                      </formulaList>
                      <userVariable reference="../../../../brick[2]/userVariable"/>
                    </brick>
                    <brick type="ChangeVariableBrick">
                      <brickId>8c4aad26-58db-4c85-acd3-207553ed52f5</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="VARIABLE_CHANGE">
                          <additionalChildren/>
                          <rightChild>
                            <additionalChildren/>
                            <type>NUMBER</type>
                            <value>2</value>
                          </rightChild>
                          <type>OPERATOR</type>
                          <value>MINUS</value>
                        </formula>
                      </formulaList>
                      <userVariable reference="../../../../../../../../object[2]/scriptList/script[2]/brickList/brick[3]/userVariable"/>
                    </brick>
                    <brick type="SetBrightnessBrick">
                      <brickId>b2c6ff01-42b7-401f-a53e-192e1a44c6ab</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="BRIGHTNESS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>50</value>
                        </formula>
                      </formulaList>
                    </brick>
                  </ifBranchBricks>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>5b745238-3c92-4c9d-a778-f96a517890b4</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Goku">
          <lookList>
            <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#0.png" name="Goku">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>3ddc9199-781b-49a8-be29-52f025cd2b19</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>686</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>149</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>2737cb8e-a664-41f5-8971-a3cf351f09f7</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>500</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>1e0f86ac-aa5a-4d19-8a33-f607a9a87364</scriptId>
            </script>
            <script type="WhenConditionScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="HideBrick">
                  <brickId>f7df3a21-a348-45ac-8e1f-746ff2ce4084</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>cb057a22-0148-4f89-8266-238aad524b40</scriptId>
              <formulaMap>
                <formula category="IF_CONDITION">
                  <additionalChildren/>
                  <leftChild>
                    <additionalChildren/>
                    <type>USER_VARIABLE</type>
                    <value>Goku</value>
                  </leftChild>
                  <rightChild>
                    <additionalChildren/>
                    <type>NUMBER</type>
                    <value>0</value>
                  </rightChild>
                  <type>OPERATOR</type>
                  <value>EQUAL</value>
                </formula>
              </formulaMap>
            </script>
            <script type="WhenConditionScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ShowBrick">
                  <brickId>e2ac327a-e2fc-4dc5-9a9e-d9147e637a88</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>3f6bdf8f-3944-4562-9ced-376edd9ab855</scriptId>
              <formulaMap>
                <formula category="IF_CONDITION">
                  <additionalChildren/>
                  <leftChild>
                    <additionalChildren/>
                    <type>USER_VARIABLE</type>
                    <value>Goku</value>
                  </leftChild>
                  <rightChild>
                    <additionalChildren/>
                    <type>NUMBER</type>
                    <value>1</value>
                  </rightChild>
                  <type>OPERATOR</type>
                  <value>EQUAL</value>
                </formula>
              </formulaMap>
            </script>
            <script type="WhenConditionScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="HideBrick">
                  <brickId>0a532467-8534-430f-a12c-dfb96cae85b0</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
                <brick type="ChangeVariableBrick">
                  <brickId>fe418157-e267-4b7a-b6d9-af237c447a37</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="VARIABLE_CHANGE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>1.0</value>
                    </formula>
                  </formulaList>
                  <userVariable type="UserVariable" serialization="custom">
                    <userVariable>
                      <default>
                        <initialIndex>7</initialIndex>
                        <deviceValueKey>95d9d2f2-a130-4569-ad92-28015f59b727</deviceValueKey>
                        <name>Inc</name>
                      </default>
                    </userVariable>
                  </userVariable>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>c98c12c7-7283-425c-af1f-1a710418b689</scriptId>
              <formulaMap>
                <formula category="IF_CONDITION">
                  <additionalChildren/>
                  <type>COLLISION_FORMULA</type>
                  <value>Goku_black </value>
                </formula>
              </formulaMap>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Vegeta">
          <lookList>
            <look fileName="vegeta___ultimate_lsw_sheet_by_qsab101_dbzqwt5_#0.png" name="vegeta">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>326f089a-59c5-4544-b1d6-7f7536beb9cf</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>737</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>149</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>e206e4be-1295-428c-9098-9c6569a79dad</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>500</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>9e7ad7b9-a377-4ea5-ae44-9075373e455d</scriptId>
            </script>
            <script type="WhenConditionScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="HideBrick">
                  <brickId>0b6f0950-054c-4a7b-9f11-58fc5940ff9b</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>9834fa1b-43f0-4b69-bf87-ddfb522ec0b9</scriptId>
              <formulaMap>
                <formula category="IF_CONDITION">
                  <additionalChildren/>
                  <leftChild>
                    <additionalChildren/>
                    <type>USER_VARIABLE</type>
                    <value>Vegeta</value>
                  </leftChild>
                  <rightChild>
                    <additionalChildren/>
                    <type>NUMBER</type>
                    <value>0</value>
                  </rightChild>
                  <type>OPERATOR</type>
                  <value>EQUAL</value>
                </formula>
              </formulaMap>
            </script>
            <script type="WhenConditionScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ShowBrick">
                  <brickId>35963409-0d46-4c76-aea6-74fb682668b0</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>9423fbf4-e432-4dc6-9cf8-127ef5b5a1af</scriptId>
              <formulaMap>
                <formula category="IF_CONDITION">
                  <additionalChildren/>
                  <leftChild>
                    <additionalChildren/>
                    <type>USER_VARIABLE</type>
                    <value>Vegeta</value>
                  </leftChild>
                  <rightChild>
                    <additionalChildren/>
                    <type>NUMBER</type>
                    <value>1</value>
                  </rightChild>
                  <type>OPERATOR</type>
                  <value>EQUAL</value>
                </formula>
              </formulaMap>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Jogar">
          <lookList>
            <look fileName="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d.png" name="Jogar">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>3907f586-88d8-4d3b-81b1-77df7598c24f</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>200</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>f5a744be-3c29-42f7-8327-32a7cdbe20ab</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>700</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>8314a198-35b3-4590-a68f-651f72072d6d</scriptId>
            </script>
            <script type="WhenConditionScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="HideBrick">
                  <brickId>e23a341a-7771-403d-9bfc-a1825303696b</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>ade7f6f6-3f7f-4ef0-ad40-e75dd7818fcf</scriptId>
              <formulaMap>
                <formula category="IF_CONDITION">
                  <additionalChildren/>
                  <leftChild>
                    <additionalChildren/>
                    <type>USER_VARIABLE</type>
                    <value>Jogar</value>
                  </leftChild>
                  <rightChild>
                    <additionalChildren/>
                    <type>NUMBER</type>
                    <value>0</value>
                  </rightChild>
                  <type>OPERATOR</type>
                  <value>EQUAL</value>
                </formula>
              </formulaMap>
            </script>
            <script type="WhenConditionScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="HideBrick">
                  <brickId>862539b4-0339-4d8b-97d2-d6b9b4a7b3ca</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>f13cf3b2-1542-4c60-abb6-ff969cb1ff67</scriptId>
              <formulaMap>
                <formula category="IF_CONDITION">
                  <additionalChildren/>
                  <leftChild>
                    <additionalChildren/>
                    <type>USER_VARIABLE</type>
                    <value>Jogar</value>
                  </leftChild>
                  <rightChild>
                    <additionalChildren/>
                    <type>NUMBER</type>
                    <value>1</value>
                  </rightChild>
                  <type>OPERATOR</type>
                  <value>EQUAL</value>
                </formula>
              </formulaMap>
            </script>
            <script type="WhenConditionScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ShowBrick">
                  <brickId>1c5f79be-a739-4cfc-97c3-5c7169d228c1</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
                <brick type="ForeverBrick">
                  <brickId>7b04b098-bfed-4899-a262-b6838ae0f577</brickId>
                  <commentedOut>false</commentedOut>
                  <loopBricks>
                    <brick type="GlideToBrick">
                      <brickId>6b64c45d-1118-4c67-bfa5-4bd86795b0f1</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="X_DESTINATION">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>0</value>
                        </formula>
                        <formula category="DURATION_IN_SECONDS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>1.0</value>
                        </formula>
                        <formula category="Y_DESTINATION">
                          <additionalChildren/>
                          <rightChild>
                            <additionalChildren/>
                            <type>NUMBER</type>
                            <value>190</value>
                          </rightChild>
                          <type>OPERATOR</type>
                          <value>MINUS</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="GlideToBrick">
                      <brickId>4b8f0a46-f241-464f-a874-6ed85484feeb</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="X_DESTINATION">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>0</value>
                        </formula>
                        <formula category="DURATION_IN_SECONDS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>1.0</value>
                        </formula>
                        <formula category="Y_DESTINATION">
                          <additionalChildren/>
                          <rightChild>
                            <additionalChildren/>
                            <type>NUMBER</type>
                            <value>200</value>
                          </rightChild>
                          <type>OPERATOR</type>
                          <value>MINUS</value>
                        </formula>
                      </formulaList>
                    </brick>
                  </loopBricks>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>f494bd76-1034-4780-99f5-68e976a30a1e</scriptId>
              <formulaMap>
                <formula category="IF_CONDITION">
                  <additionalChildren/>
                  <leftChild>
                    <additionalChildren/>
                    <type>USER_VARIABLE</type>
                    <value>Jogar</value>
                  </leftChild>
                  <rightChild>
                    <additionalChildren/>
                    <type>NUMBER</type>
                    <value>2</value>
                  </rightChild>
                  <type>OPERATOR</type>
                  <value>EQUAL</value>
                </formula>
              </formulaMap>
            </script>
            <script type="WhenConditionScript" posX="0.0" posY="0.0">
              <brickList/>
              <commentedOut>false</commentedOut>
              <scriptId>a6983e33-49a8-46b6-8e13-b49e2780909a</scriptId>
              <formulaMap>
                <formula category="IF_CONDITION">
                  <additionalChildren/>
                  <leftChild>
                    <additionalChildren/>
                    <type>USER_VARIABLE</type>
                    <value>Black</value>
                  </leftChild>
                  <rightChild>
                    <additionalChildren/>
                    <type>NUMBER</type>
                    <value>1</value>
                  </rightChild>
                  <type>OPERATOR</type>
                  <value>EQUAL</value>
                </formula>
              </formulaMap>
            </script>
            <script type="WhenScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="IfThenLogicBeginBrick">
                  <brickId>d4f7ae4e-b9f1-45a8-9bf6-b56cc11dc663</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="IF_CONDITION">
                      <additionalChildren/>
                      <leftChild>
                        <additionalChildren/>
                        <type>USER_VARIABLE</type>
                        <value>Black</value>
                      </leftChild>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>1</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>EQUAL</value>
                    </formula>
                  </formulaList>
                  <ifBranchBricks>
                    <brick type="SceneStartBrick">
                      <brickId>1d6085f7-3961-4bbf-aab1-199040830238</brickId>
                      <commentedOut>false</commentedOut>
                      <sceneToStart>Luta (2)</sceneToStart>
                    </brick>
                  </ifBranchBricks>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>6047309b-aad3-4d83-b225-ec756599ed1e</scriptId>
            </script>
            <script type="WhenScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="IfThenLogicBeginBrick">
                  <brickId>c2f8202b-ae62-4c7d-b04c-b89d49ea48a8</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="IF_CONDITION">
                      <additionalChildren/>
                      <leftChild>
                        <additionalChildren/>
                        <type>USER_VARIABLE</type>
                        <value>Goku</value>
                      </leftChild>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>1</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>EQUAL</value>
                    </formula>
                  </formulaList>
                  <ifBranchBricks>
                    <brick type="SceneStartBrick">
                      <brickId>844e4e40-1d50-4f07-8b8c-be3c69dac9d2</brickId>
                      <commentedOut>false</commentedOut>
                      <sceneToStart>Luta</sceneToStart>
                    </brick>
                  </ifBranchBricks>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>30ca9f39-7af1-4aec-8a28-2c7403f7350a</scriptId>
            </script>
            <script type="WhenConditionScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="HideBrick">
                  <brickId>510e4481-afcd-464b-8c89-6d66efd3d018</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>429a5518-60c4-4a06-a2ea-7535e103906e</scriptId>
              <formulaMap>
                <formula category="IF_CONDITION">
                  <additionalChildren/>
                  <leftChild>
                    <additionalChildren/>
                    <type>USER_VARIABLE</type>
                    <value>Inc</value>
                  </leftChild>
                  <rightChild>
                    <additionalChildren/>
                    <type>NUMBER</type>
                    <value>1</value>
                  </rightChild>
                  <type>OPERATOR</type>
                  <value>EQUAL</value>
                </formula>
              </formulaMap>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Face_Goku_Black">
          <lookList>
            <look fileName="goku_black___ulsw_sprite_sheet_by_songoku0911_ddebcai.png" name="Goku_Black">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>15400412-33a5-42b8-9514-a52d38d1662a</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>514</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>297</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>edc1748b-1d7d-4d28-973d-2f1831c40f93</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>400</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>94c3f25f-958d-4ca4-9dc0-c33f3984a5f5</scriptId>
            </script>
            <script type="WhenScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetBrightnessBrick">
                  <brickId>fc8fa357-0e08-496c-8be0-c269d7568e5a</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="BRIGHTNESS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>100</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="ChangeVariableBrick">
                  <brickId>efa8de22-608f-4198-8841-a15e731b30ca</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="VARIABLE_CHANGE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>1.0</value>
                    </formula>
                  </formulaList>
                  <userVariable type="UserVariable" serialization="custom">
                    <userVariable>
                      <default>
                        <initialIndex>5</initialIndex>
                        <deviceValueKey>7208b406-04f0-4e10-ba95-fb778033e78c</deviceValueKey>
                        <name>Black</name>
                      </default>
                    </userVariable>
                  </userVariable>
                </brick>
                <brick type="ChangeVariableBrick">
                  <brickId>295a6023-115a-44d5-85a0-acb77aed43e3</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="VARIABLE_CHANGE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>1.0</value>
                    </formula>
                  </formulaList>
                  <userVariable reference="../../../../../../object[2]/scriptList/script[2]/brickList/brick[3]/userVariable"/>
                </brick>
                <brick type="IfThenLogicBeginBrick">
                  <brickId>00ed2199-5f4b-428a-af98-9ba8dd737749</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="IF_CONDITION">
                      <additionalChildren/>
                      <leftChild>
                        <additionalChildren/>
                        <type>USER_VARIABLE</type>
                        <value>Black</value>
                      </leftChild>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>2</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>EQUAL</value>
                    </formula>
                  </formulaList>
                  <ifBranchBricks>
                    <brick type="ChangeVariableBrick">
                      <brickId>3eca3cce-f8d9-44b1-89d1-e262e1d25d83</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="VARIABLE_CHANGE">
                          <additionalChildren/>
                          <rightChild>
                            <additionalChildren/>
                            <type>NUMBER</type>
                            <value>2</value>
                          </rightChild>
                          <type>OPERATOR</type>
                          <value>MINUS</value>
                        </formula>
                      </formulaList>
                      <userVariable reference="../../../../brick[2]/userVariable"/>
                    </brick>
                    <brick type="ChangeVariableBrick">
                      <brickId>852251df-fb74-4eac-98c0-e0328673b4c8</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="VARIABLE_CHANGE">
                          <additionalChildren/>
                          <rightChild>
                            <additionalChildren/>
                            <type>NUMBER</type>
                            <value>2</value>
                          </rightChild>
                          <type>OPERATOR</type>
                          <value>MINUS</value>
                        </formula>
                      </formulaList>
                      <userVariable reference="../../../../../../../../object[2]/scriptList/script[2]/brickList/brick[3]/userVariable"/>
                    </brick>
                    <brick type="SetBrightnessBrick">
                      <brickId>a585df52-4f93-4e35-ac59-8f0dd1863031</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="BRIGHTNESS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>50</value>
                        </formula>
                      </formulaList>
                    </brick>
                  </ifBranchBricks>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>b3849439-c6bf-404a-a769-9b6ce928d3d8</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Goku_black ">
          <lookList>
            <look fileName="goku_black___ulsw_sprite_sheet_by_songoku0911_ddebcai_#0.png" name="Goku_black ">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>da849793-76c1-4ff4-b0c7-c28ee45bf6ac</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>686</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>149</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>4f14ed27-755b-4b58-8e18-c6b86e0792c2</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>500</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>c763d7c7-0a2c-47d7-8bcc-a128488e4e77</scriptId>
            </script>
            <script type="WhenConditionScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="HideBrick">
                  <brickId>59e44b5d-869d-40de-820f-42dc0ca87ac2</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>51aa5de4-93de-4a3b-87bc-c65d577d0556</scriptId>
              <formulaMap>
                <formula category="IF_CONDITION">
                  <additionalChildren/>
                  <leftChild>
                    <additionalChildren/>
                    <type>USER_VARIABLE</type>
                    <value>Black</value>
                  </leftChild>
                  <rightChild>
                    <additionalChildren/>
                    <type>NUMBER</type>
                    <value>0</value>
                  </rightChild>
                  <type>OPERATOR</type>
                  <value>EQUAL</value>
                </formula>
              </formulaMap>
            </script>
            <script type="WhenConditionScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ShowBrick">
                  <brickId>c39cf237-31ac-4433-adb1-89bcc568e67c</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>ff062ce7-704b-4e5e-b92b-3919e1e83ec4</scriptId>
              <formulaMap>
                <formula category="IF_CONDITION">
                  <additionalChildren/>
                  <leftChild>
                    <additionalChildren/>
                    <type>USER_VARIABLE</type>
                    <value>Black</value>
                  </leftChild>
                  <rightChild>
                    <additionalChildren/>
                    <type>NUMBER</type>
                    <value>1</value>
                  </rightChild>
                  <type>OPERATOR</type>
                  <value>EQUAL</value>
                </formula>
              </formulaMap>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
      </objectList>
    </scene>
    <scene>
      <name>Cutscene</name>
      <objectList>
        <object type="Sprite" name="Fundo">
          <lookList>
            <look fileName="imnjjhages.jpeg" name="imnjjhages">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetSizeToBrick">
                  <brickId>9c84a562-c831-4609-a8ad-332113487d23</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>450</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>10b0ac30-e16e-46ab-a74a-31858c336662</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Gk">
          <lookList>
            <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#1.png" name="1">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#0.png" name="2">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#2.png" name="3">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#3.png" name="4">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#4.png" name="5">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#5.png" name="6">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#6.png" name="7">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#7.png" name="8">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>b60234c6-48f3-4dca-b1d8-980043bc611a</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>965</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>352</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>eb6003a8-695c-4f02-a412-6720d011f34c</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>500</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="RepeatBrick">
                  <brickId>fd4f4172-c7d7-4e9c-9467-d1e38a6d45ca</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIMES_TO_REPEAT">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>10</value>
                    </formula>
                  </formulaList>
                  <loopBricks>
                    <brick type="SetLookBrick">
                      <brickId>f80dc697-2757-4a1b-8294-1641fabb121c</brickId>
                      <commentedOut>false</commentedOut>
                      <look reference="../../../../../../../lookList/look"/>
                    </brick>
                    <brick type="WaitBrick">
                      <brickId>21ed0a7d-68b1-4a47-9587-a2f8a646a4e6</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="TIME_TO_WAIT_IN_SECONDS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>0.4</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetLookBrick">
                      <brickId>766d24c0-0c1c-4f84-9296-9674fd88998c</brickId>
                      <commentedOut>false</commentedOut>
                      <look reference="../../../../../../../lookList/look[2]"/>
                    </brick>
                    <brick type="WaitBrick">
                      <brickId>d55d53b0-5d5a-4d33-9a5b-a45412d5dc9e</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="TIME_TO_WAIT_IN_SECONDS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>0.4</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetLookBrick">
                      <brickId>f6c94da6-6238-4d3a-890f-f3d912b9e727</brickId>
                      <commentedOut>false</commentedOut>
                      <look reference="../../../../../../../lookList/look[3]"/>
                    </brick>
                    <brick type="WaitBrick">
                      <brickId>0a4623bd-d4a9-4979-99fe-bbc5beaec0f6</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="TIME_TO_WAIT_IN_SECONDS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>0.4</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetLookBrick">
                      <brickId>047482ba-114f-4156-a0d6-405fee4308b8</brickId>
                      <commentedOut>false</commentedOut>
                      <look reference="../../../../../../../lookList/look[4]"/>
                    </brick>
                    <brick type="WaitBrick">
                      <brickId>98580263-c452-436c-b2a3-4106486f5ded</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="TIME_TO_WAIT_IN_SECONDS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>0.3</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetLookBrick">
                      <brickId>d35a5027-4316-4d4a-bf32-ab4fc165b6fc</brickId>
                      <commentedOut>false</commentedOut>
                      <look reference="../../../../../../../lookList/look[5]"/>
                    </brick>
                    <brick type="WaitBrick">
                      <brickId>d3a19570-7529-44c2-bdb7-cd9235a8469c</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="TIME_TO_WAIT_IN_SECONDS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>0.3</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetLookBrick">
                      <brickId>148b449d-5636-4d7c-bea7-c6648ad60976</brickId>
                      <commentedOut>false</commentedOut>
                      <look reference="../../../../../../../lookList/look[6]"/>
                    </brick>
                    <brick type="WaitBrick">
                      <brickId>b6041375-e23a-4d98-95c6-062e8c5bbe0d</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="TIME_TO_WAIT_IN_SECONDS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>0.5</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetLookBrick">
                      <brickId>88435686-6203-441a-ac97-7e2bb3fae9c4</brickId>
                      <commentedOut>false</commentedOut>
                      <look reference="../../../../../../../lookList/look[7]"/>
                    </brick>
                    <brick type="WaitBrick">
                      <brickId>2e780fa8-15cb-4f17-a759-c16ae2a9e141</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="TIME_TO_WAIT_IN_SECONDS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>0.4</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetLookBrick">
                      <brickId>762c948a-7f34-465a-ae54-e1341b231ca1</brickId>
                      <commentedOut>false</commentedOut>
                      <look reference="../../../../../../../lookList/look[8]"/>
                    </brick>
                  </loopBricks>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>26d72ed8-8021-4e30-b98b-5f4d6489d4fb</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="L">
          <lookList>
            <look fileName="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d_#1.png" name="L">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d_#2.png" name="O">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d_#3.png" name="A">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d_#4.png" name="D">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d_#5.png" name="I">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d_#6.png" name="N">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d_#0.png" name="G">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>021b1124-439d-4886-bdfc-d6559951c05a</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>1158</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>181</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>3258d39e-74c9-4103-94f3-3554df3f1a46</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>600</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>84a9e963-466c-4282-93bb-4fce8f3a5d4e</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="O">
          <lookList>
            <look fileName="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d_#7.png" name="O">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>1bedbb16-a99d-4376-9614-36afb9fe4ff0</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>1100</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>181</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>ba160270-c5b1-4c87-9828-4e8d57cc3fad</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>600</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>742e0d49-7c10-456e-bb16-42d522fde501</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="A">
          <lookList>
            <look fileName="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d_#9.png" name="A">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>082a52df-18f6-4b34-97de-95ec3594ca03</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>1036</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>183</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>a86631d1-37dc-43c0-bf07-e344d2fef51c</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>600</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>296a6b15-2561-41fe-89cb-70b51b4b2a65</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="D">
          <lookList>
            <look fileName="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d_#8.png" name="D">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>d9a436e3-6b99-43b9-a39d-6b2b04b3ca93</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>967</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>178</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>7dbe7fd2-012d-470e-ac95-aceecaed1bde</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>600</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>40985acd-f9aa-4a21-8e54-d42c0e1ff730</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="I">
          <lookList>
            <look fileName="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d_#10.png" name="I">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>d3ea8e2e-ced3-4b9b-b072-fd62f4676933</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>917</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>175</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>9575c6d6-181c-4bd6-a062-badf1c3a505c</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>600</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>d8af085a-e209-4e19-926b-9b7831e3cf23</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="N">
          <lookList>
            <look fileName="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d_#11.png" name="N">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>5ca76a99-50d3-4f2a-bbfe-a9362b65ca7d</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>859</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>175</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>b8f710ee-c8c6-4066-84a3-54dfc31e091b</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>600</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>fd8880a3-accd-40da-95d7-de4ebe9786e7</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="G">
          <lookList>
            <look fileName="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d_#12.png" name="G">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>5aaef94d-174f-4699-b603-a547ea8d0228</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>788</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>177</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>1c42dbf5-d1c5-45da-8aaf-fa41a03d8d41</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>600</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>238e90b1-122e-4428-9e2f-4148e8f1c7b5</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name=". ">
          <lookList>
            <look fileName="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d_#15.png" name=".  (1)">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>d8c450a7-84e0-4eed-8379-724e11cfe7a0</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>737</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>193</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>31d750bc-6961-42f9-a95c-9390fd57c79d</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>600</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>9a6581bc-c1d0-4e75-b38d-6c280213d2a0</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name=". 2">
          <lookList>
            <look fileName="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d.png" name=". ">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d_#13.png" name=".  (1)">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d_#14.png" name=". (1)">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>62c11217-d725-42ed-aef8-1eb7a5bfe214</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>707</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>193</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>b1a9f8b5-19d7-4d49-8ffe-abec570336b4</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>600</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>d14a9392-2230-4ba7-82bb-5be209b295c3</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name=". 3">
          <lookList>
            <look fileName="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d_#16.png" name=". (1)">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>81c2cc5b-8d17-4f2e-aeb2-58f2c2fed2b9</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>676</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>193</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>2935e40a-0f97-4921-a871-35017e23504d</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>600</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>97f00832-1185-4fc9-9f24-0b64f1e1f0b5</scriptId>
            </script>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="RepeatBrick">
                  <brickId>6fd748d5-04d0-4981-b553-57f979afbfb6</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIMES_TO_REPEAT">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>1</value>
                    </formula>
                  </formulaList>
                  <loopBricks>
                    <brick type="SetSizeToBrick">
                      <brickId>d58bf913-2d49-4dbc-bb46-b3a4f8ee1cf5</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="SIZE">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>0</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="WaitBrick">
                      <brickId>708b3655-735b-4201-bdcc-40ee8187ecf9</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="TIME_TO_WAIT_IN_SECONDS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>1.0</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetSizeToBrick">
                      <brickId>180c921d-7114-4b49-bd75-3f0960bfbe43</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="SIZE">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>600</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="WaitBrick">
                      <brickId>706d9dd9-d7da-4917-8b83-a6c31aed9ec6</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="TIME_TO_WAIT_IN_SECONDS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>1.0</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetSizeToBrick">
                      <brickId>2d397944-d224-48bc-9eee-3a3178a9b847</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="SIZE">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>0</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="WaitBrick">
                      <brickId>909da46d-14e3-434c-a148-ace6d82eeb29</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="TIME_TO_WAIT_IN_SECONDS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>1.0</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetSizeToBrick">
                      <brickId>65012ee8-3c75-4293-ab72-772dbd726671</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="SIZE">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>600</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="WaitBrick">
                      <brickId>441f18d8-bb59-4dbf-b0d5-3c19f4ae5010</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="TIME_TO_WAIT_IN_SECONDS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>1.0</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetSizeToBrick">
                      <brickId>a93ed16b-ed89-417d-ad05-6aca197b2c13</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="SIZE">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>0</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="WaitBrick">
                      <brickId>3b249792-ca79-4a0d-8ee6-abfa2f3ed201</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="TIME_TO_WAIT_IN_SECONDS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>1.0</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetSizeToBrick">
                      <brickId>e32f8116-cdb3-4a6b-866c-557378a530c4</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="SIZE">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>600</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="WaitBrick">
                      <brickId>35aad0b2-db75-4ab3-8802-8b0196bd18c5</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="TIME_TO_WAIT_IN_SECONDS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>1.0</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetSizeToBrick">
                      <brickId>4c4d2562-4a03-4475-8369-3de285fe0c3b</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="SIZE">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>0</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="WaitBrick">
                      <brickId>6166e28f-4949-4e42-9dc3-77c4b723e34f</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="TIME_TO_WAIT_IN_SECONDS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>1.0</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetSizeToBrick">
                      <brickId>3886beb5-fff9-4de5-88c8-a2c6a819b5a3</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="SIZE">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>600</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="WaitBrick">
                      <brickId>a972a22a-206a-4985-b8a9-04a3a20a129c</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="TIME_TO_WAIT_IN_SECONDS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>1.0</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetSizeToBrick">
                      <brickId>74d7053a-376d-4066-a36c-a586078e213b</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="SIZE">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>0</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="WaitBrick">
                      <brickId>ab646852-9b2c-4579-bfbe-7e3643b60e7c</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="TIME_TO_WAIT_IN_SECONDS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>1.0</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetSizeToBrick">
                      <brickId>db5c85eb-369c-4aa5-ad28-bafb3b2f23bb</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="SIZE">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>600</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="WaitBrick">
                      <brickId>adb5cfa8-69dc-4c2b-81b9-b88c580e83a7</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="TIME_TO_WAIT_IN_SECONDS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>1.0</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetVariableBrick">
                      <brickId>e576565f-1970-4614-af74-6c697e7bb0a3</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="VARIABLE">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>1.0</value>
                        </formula>
                      </formulaList>
                      <userVariable type="UserVariable" serialization="custom">
                        <userVariable>
                          <default>
                            <initialIndex>6</initialIndex>
                            <deviceValueKey>5e9a652e-026b-4b47-9206-af3d806fc4c7</deviceValueKey>
                            <name>Iniciar </name>
                          </default>
                        </userVariable>
                      </userVariable>
                    </brick>
                  </loopBricks>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>1fd5ecef-f3eb-43d4-9542-b96977f938d3</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Iniciar ">
          <lookList>
            <look fileName="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d_#17.png" name="Iniciar ">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>8839028f-410e-4fd1-a449-3dba2f5a9187</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>190</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>85cbefc5-46e8-494c-9784-df3e3be5aae3</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>600</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="HideBrick">
                  <brickId>9433cae5-33ba-4e52-97c3-7d456f6281e1</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>cb4f426f-3519-4503-aaab-da99cc9521e0</scriptId>
            </script>
            <script type="WhenConditionScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ShowBrick">
                  <brickId>239dbe98-335b-461c-aa0d-bbbcd40baa13</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>a5bfd7ea-d4e5-4ebd-b73b-465ce31cbb0b</scriptId>
              <formulaMap>
                <formula category="IF_CONDITION">
                  <additionalChildren/>
                  <leftChild>
                    <additionalChildren/>
                    <type>USER_VARIABLE</type>
                    <value>Iniciar </value>
                  </leftChild>
                  <rightChild>
                    <additionalChildren/>
                    <type>NUMBER</type>
                    <value>1</value>
                  </rightChild>
                  <type>OPERATOR</type>
                  <value>EQUAL</value>
                </formula>
              </formulaMap>
            </script>
            <script type="WhenScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetSizeToBrick">
                  <brickId>e3caf645-83a8-465f-8214-6b5fcccb329b</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>500</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="WaitBrick">
                  <brickId>6c64f9ba-7043-4c32-8dee-9e655fbd9dba</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.1</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>fa53372c-80f8-4678-960d-72bf3fc342d7</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>600</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="WaitBrick">
                  <brickId>1a2abd52-5ac2-455e-a9e5-6fed536460b8</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.2</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SceneStartBrick">
                  <brickId>b22483cd-13a3-4de4-bb52-91e4b942c6a4</brickId>
                  <commentedOut>false</commentedOut>
                  <sceneToStart>Luta</sceneToStart>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>63134e4b-dc86-4f2b-98ea-feeeb0e5c9da</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
      </objectList>
    </scene>
    <scene>
      <name>Luta</name>
      <objectList>
        <object type="Sprite" name="Fundo">
          <lookList>
            <look fileName="dragon-ball-z-championship-virtual-background-for-zoom (1).jpeg" name="dragon-ball-z-championship-virtual-background-for-zoom (1)">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetSizeToBrick">
                  <brickId>19ffae38-5ada-4d35-a9a0-05b995decde6</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>150</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>41e9fda2-8df5-4c70-930e-61ca28f20669</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="&#xa;Direita">
          <lookList>
            <look fileName="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d.png" name="&#xa;Direita">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>fc2ce5fc-e43f-45ad-a78d-28b53a5b6282</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>720</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>422</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>5108a2fb-44a1-433c-a176-955bdfeafc6c</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>700</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetTransparencyBrick">
                  <brickId>c2b19e65-f143-4d9a-9c20-25b3f0f5f6ac</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TRANSPARENCY">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>20</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>bed59acc-e5e4-432d-9fec-8f6a6266d0c5</scriptId>
            </script>
            <script type="WhenScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetTransparencyBrick">
                  <brickId>d0179079-29a0-4539-b343-4ed5b0567100</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TRANSPARENCY">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>15</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="WaitBrick">
                  <brickId>32d89c97-8b7d-4464-9b43-96933ae3e5af</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.2</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetTransparencyBrick">
                  <brickId>299cd6af-e95c-4acc-b50c-04103eb03f55</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TRANSPARENCY">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>20</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="BroadcastBrick">
                  <brickId>7c45eef8-dcf3-495d-a935-634a6d2af7ed</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Andar Direita</broadcastMessage>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>0bdc117a-6137-4033-bb2c-21862b703ad7</scriptId>
            </script>
            <script type="WhenScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="RepeatUntilBrick">
                  <brickId>2cddb6bb-2e5b-4663-9efd-e40db878f273</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="REPEAT_UNTIL_CONDITION">
                      <additionalChildren/>
                      <leftChild>
                        <additionalChildren/>
                        <type>SENSOR</type>
                        <value>FINGER_TOUCHED</value>
                      </leftChild>
                      <rightChild>
                        <additionalChildren/>
                        <type>FUNCTION</type>
                        <value>FALSE</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>EQUAL</value>
                    </formula>
                  </formulaList>
                  <loopBricks>
                    <brick type="BroadcastBrick">
                      <brickId>6369a982-ffeb-4c8f-ba10-ca9c860d864f</brickId>
                      <commentedOut>false</commentedOut>
                      <broadcastMessage>Andar Direita</broadcastMessage>
                    </brick>
                  </loopBricks>
                </brick>
                <brick type="BroadcastBrick">
                  <brickId>15031813-4572-4e2e-9f0b-1eb062ceebd9</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Parar</broadcastMessage>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>033abe2b-047a-4ce9-a55b-492bbaf380ff</scriptId>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="HideBrick">
                  <brickId>3e094765-d9ac-479c-b9f4-1f5e6df68493</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>66d0ca81-e4ea-4439-8472-fe960b173db0</scriptId>
              <receivedMessage>Mortegoku</receivedMessage>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Esquerda ">
          <lookList>
            <look fileName="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d_#0.png" name="&#xa;Direita">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>47429de1-09f3-4c64-a5f1-deace86e1c74</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>1064</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>420</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>53e8e4eb-6757-4a17-972c-cc7f26d497ae</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>700</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetTransparencyBrick">
                  <brickId>ba86cfb6-07de-4dd6-b33a-3e6d985b1bdf</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TRANSPARENCY">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>20</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>c9707e0a-69dd-4768-bc6b-c423ab182980</scriptId>
            </script>
            <script type="WhenScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetTransparencyBrick">
                  <brickId>392ed563-6e2b-424d-9ea6-8cda4b83ce5c</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TRANSPARENCY">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>15</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="WaitBrick">
                  <brickId>b69a033b-e4be-4db3-9a6a-f192e1fd1fb6</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.2</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetTransparencyBrick">
                  <brickId>24b0b670-c887-4353-84e3-ae155df81bde</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TRANSPARENCY">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>20</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="BroadcastBrick">
                  <brickId>a28464a2-e125-4511-8aef-2477a896a66a</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Andar Esquerda </broadcastMessage>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>23ba5cbc-b150-4f5b-b32c-0419ba22eaf4</scriptId>
            </script>
            <script type="WhenScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="RepeatUntilBrick">
                  <brickId>24fbc4d5-310d-4140-af09-25b04e0968da</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="REPEAT_UNTIL_CONDITION">
                      <additionalChildren/>
                      <leftChild>
                        <additionalChildren/>
                        <type>SENSOR</type>
                        <value>FINGER_TOUCHED</value>
                      </leftChild>
                      <rightChild>
                        <additionalChildren/>
                        <type>FUNCTION</type>
                        <value>FALSE</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>EQUAL</value>
                    </formula>
                  </formulaList>
                  <loopBricks>
                    <brick type="BroadcastBrick">
                      <brickId>a8a8aa3c-3863-47d9-bae6-7c97a8daa771</brickId>
                      <commentedOut>false</commentedOut>
                      <broadcastMessage>Andar Esquerda </broadcastMessage>
                    </brick>
                  </loopBricks>
                </brick>
                <brick type="BroadcastBrick">
                  <brickId>027b2212-f6be-4204-a2e5-73e5c4a26c23</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Parar</broadcastMessage>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>df980697-971f-482a-84b1-c7958fdb1b7d</scriptId>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="HideBrick">
                  <brickId>f0593700-fc4b-449b-9745-e71581aed009</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>e5307bb9-3f22-440e-a3e5-7df173885e63</scriptId>
              <receivedMessage>Mortegoku</receivedMessage>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Goku">
          <lookList>
            <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#2.png" name="Parado">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#0.png" name="Esquerda ">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd.png" name="Direita 1">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#1.png" name="Direita 2">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#3.png" name="Soco 1">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#4.png" name="Soco 2">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#10.png" name="Kibast">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#11.png" name="Morte 1">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#12.png" name="Morte 2">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="IfOnEdgeBounceBrick">
                  <brickId>12aa0080-fa92-4107-8565-9511a50f35f0</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
                <brick type="PlaceAtBrick">
                  <brickId>92fd89fa-59a9-46b1-a1c6-9b60ca9f7571</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>1019</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>149</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>1f57a71d-bdc8-49f0-bf97-b608a9ce8441</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>550</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="ForeverBrick">
                  <brickId>7a12d4b8-afc1-4d75-8b1f-a1edd5c89f8e</brickId>
                  <commentedOut>false</commentedOut>
                  <loopBricks>
                    <brick type="PointToBrick">
                      <brickId>cad05e37-4adc-433d-ae25-6585dd6dbc04</brickId>
                      <commentedOut>false</commentedOut>
                      <pointedObject type="Sprite" name="Vegeta">
                        <lookList>
                          <look fileName="vegeta___ultimate_lsw_sheet_by_qsab101_dbzqwt5_#0.png" name="vegeta">
                            <isWebRequest>false</isWebRequest>
                            <valid>true</valid>
                          </look>
                          <look fileName="vegeta___ultimate_lsw_sheet_by_qsab101_dbzqwt5_#2.png" name="Voando">
                            <isWebRequest>false</isWebRequest>
                            <valid>true</valid>
                          </look>
                          <look fileName="vegeta___ultimate_lsw_sheet_by_qsab101_dbzqwt5.png" name="Soco 1">
                            <isWebRequest>false</isWebRequest>
                            <valid>true</valid>
                          </look>
                          <look fileName="vegeta___ultimate_lsw_sheet_by_qsab101_dbzqwt5_#1.png" name="Soco 2">
                            <isWebRequest>false</isWebRequest>
                            <valid>true</valid>
                          </look>
                          <look fileName="vegeta___ultimate_lsw_sheet_by_qsab101_dbzqwt5_#3.png" name="Soco 3">
                            <isWebRequest>false</isWebRequest>
                            <valid>true</valid>
                          </look>
                          <look fileName="vegeta___ultimate_lsw_sheet_by_qsab101_dbzqwt5_#4.png" name="Soco 4">
                            <isWebRequest>false</isWebRequest>
                            <valid>true</valid>
                          </look>
                          <look fileName="vegeta___ultimate_lsw_sheet_by_qsab101_dbzqwt5_#5.png" name="Soco 5">
                            <isWebRequest>false</isWebRequest>
                            <valid>true</valid>
                          </look>
                          <look fileName="vegeta___ultimate_lsw_sheet_by_qsab101_dbzqwt5_#6.png" name="Morte 1">
                            <isWebRequest>false</isWebRequest>
                            <valid>true</valid>
                          </look>
                          <look fileName="vegeta___ultimate_lsw_sheet_by_qsab101_dbzqwt5_#7.png" name="Morte 2">
                            <isWebRequest>false</isWebRequest>
                            <valid>true</valid>
                          </look>
                        </lookList>
                        <soundList/>
                        <scriptList>
                          <script type="StartScript" posX="0.0" posY="0.0">
                            <brickList>
                              <brick type="PlaceAtBrick">
                                <brickId>0fe5f357-11f3-4400-8ebb-a8c6b428b560</brickId>
                                <commentedOut>false</commentedOut>
                                <formulaList>
                                  <formula category="X_POSITION">
                                    <additionalChildren/>
                                    <type>NUMBER</type>
                                    <value>744</value>
                                  </formula>
                                  <formula category="Y_POSITION">
                                    <additionalChildren/>
                                    <rightChild>
                                      <additionalChildren/>
                                      <type>NUMBER</type>
                                      <value>259</value>
                                    </rightChild>
                                    <type>OPERATOR</type>
                                    <value>MINUS</value>
                                  </formula>
                                </formulaList>
                              </brick>
                              <brick type="SetSizeToBrick">
                                <brickId>cfc4c9ed-ed4a-411c-bbee-2ef3b05e2dd0</brickId>
                                <commentedOut>false</commentedOut>
                                <formulaList>
                                  <formula category="SIZE">
                                    <additionalChildren/>
                                    <type>NUMBER</type>
                                    <value>500</value>
                                  </formula>
                                </formulaList>
                              </brick>
                            </brickList>
                            <commentedOut>false</commentedOut>
                            <scriptId>ccd6f172-5785-4669-b232-4108aec94449</scriptId>
                          </script>
                          <script type="StartScript" posX="0.0" posY="0.0">
                            <brickList>
                              <brick type="ForeverBrick">
                                <brickId>0ed0812b-536e-47a2-8a8f-fb3aa1b13ba6</brickId>
                                <commentedOut>false</commentedOut>
                                <loopBricks>
                                  <brick type="PointToBrick">
                                    <brickId>f3eccad8-ada3-4f62-a488-6d9297a50b8b</brickId>
                                    <commentedOut>false</commentedOut>
                                    <pointedObject reference="../../../../../../../../../../../../../.."/>
                                  </brick>
                                  <brick type="SetRotationStyleBrick">
                                    <brickId>be02bad8-5482-4c41-be3e-017d0e47ae23</brickId>
                                    <commentedOut>false</commentedOut>
                                    <selection>0</selection>
                                  </brick>
                                </loopBricks>
                              </brick>
                            </brickList>
                            <commentedOut>false</commentedOut>
                            <scriptId>b4f145b2-c6e1-4344-a071-ca67fd4925d1</scriptId>
                          </script>
                          <script type="StartScript" posX="0.0" posY="0.0">
                            <brickList>
                              <brick type="ForeverBrick">
                                <brickId>7cfa50bd-75e0-40b7-baff-077211dd2c2b</brickId>
                                <commentedOut>false</commentedOut>
                                <loopBricks>
                                  <brick type="WaitBrick">
                                    <brickId>e22d22ff-9f9b-412f-88dd-222cec83bcaf</brickId>
                                    <commentedOut>false</commentedOut>
                                    <formulaList>
                                      <formula category="TIME_TO_WAIT_IN_SECONDS">
                                        <additionalChildren/>
                                        <type>NUMBER</type>
                                        <value>2</value>
                                      </formula>
                                    </formulaList>
                                  </brick>
                                  <brick type="RepeatUntilBrick">
                                    <brickId>b6874cc8-350f-406c-9522-5a987581bbbe</brickId>
                                    <commentedOut>false</commentedOut>
                                    <formulaList>
                                      <formula category="REPEAT_UNTIL_CONDITION">
                                        <additionalChildren/>
                                        <leftChild>
                                          <additionalChildren/>
                                          <type>COLLISION_FORMULA</type>
                                          <value>Goku</value>
                                        </leftChild>
                                        <rightChild>
                                          <additionalChildren/>
                                          <type>FUNCTION</type>
                                          <value>TRUE</value>
                                        </rightChild>
                                        <type>OPERATOR</type>
                                        <value>EQUAL</value>
                                      </formula>
                                    </formulaList>
                                    <loopBricks>
                                      <brick type="MoveNStepsBrick">
                                        <brickId>e439a56f-7008-4165-970e-409a7f8b9b52</brickId>
                                        <commentedOut>false</commentedOut>
                                        <formulaList>
                                          <formula category="STEPS">
                                            <additionalChildren/>
                                            <type>NUMBER</type>
                                            <value>7</value>
                                          </formula>
                                        </formulaList>
                                      </brick>
                                      <brick type="SetLookBrick">
                                        <brickId>bdccc4c5-8b57-42d1-bdba-85b7a198d1b1</brickId>
                                        <commentedOut>false</commentedOut>
                                        <look reference="../../../../../../../../../lookList/look[2]"/>
                                      </brick>
                                    </loopBricks>
                                  </brick>
                                </loopBricks>
                              </brick>
                            </brickList>
                            <commentedOut>false</commentedOut>
                            <scriptId>634a53ba-4413-41fc-a75e-72a1d97452de</scriptId>
                          </script>
                          <script type="StartScript" posX="0.0" posY="0.0">
                            <brickList>
                              <brick type="ForeverBrick">
                                <brickId>274f62ee-18a4-4037-a88f-41e77b50870f</brickId>
                                <commentedOut>false</commentedOut>
                                <loopBricks>
                                  <brick type="IfThenLogicBeginBrick">
                                    <brickId>528601ac-79a6-4f6d-94dd-992b8be6d606</brickId>
                                    <commentedOut>false</commentedOut>
                                    <formulaList>
                                      <formula category="IF_CONDITION">
                                        <additionalChildren/>
                                        <leftChild>
                                          <additionalChildren/>
                                          <type>COLLISION_FORMULA</type>
                                          <value>Goku</value>
                                        </leftChild>
                                        <rightChild>
                                          <additionalChildren/>
                                          <type>FUNCTION</type>
                                          <value>TRUE</value>
                                        </rightChild>
                                        <type>OPERATOR</type>
                                        <value>EQUAL</value>
                                      </formula>
                                    </formulaList>
                                    <ifBranchBricks>
                                      <brick type="SetLookBrick">
                                        <brickId>3be3d22b-8733-40b5-b1b3-0b24f9706c08</brickId>
                                        <commentedOut>false</commentedOut>
                                        <look reference="../../../../../../../../../lookList/look[3]"/>
                                      </brick>
                                      <brick type="ChangeVariableBrick">
                                        <brickId>a5df281e-7859-4a55-a247-2e0353f2fc28</brickId>
                                        <commentedOut>false</commentedOut>
                                        <formulaList>
                                          <formula category="VARIABLE_CHANGE">
                                            <additionalChildren/>
                                            <rightChild>
                                              <additionalChildren/>
                                              <type>NUMBER</type>
                                              <value>1</value>
                                            </rightChild>
                                            <type>OPERATOR</type>
                                            <value>MINUS</value>
                                          </formula>
                                        </formulaList>
                                        <userVariable type="UserVariable" serialization="custom">
                                          <userVariable>
                                            <default>
                                              <initialIndex>3</initialIndex>
                                              <deviceValueKey>d1a75b16-c215-47dd-a4bf-a3f251bbdfe1</deviceValueKey>
                                              <name>Vida_Goku</name>
                                            </default>
                                          </userVariable>
                                        </userVariable>
                                      </brick>
                                      <brick type="WaitBrick">
                                        <brickId>89cb9b98-bb79-4a72-9bf1-b72b851f7743</brickId>
                                        <commentedOut>false</commentedOut>
                                        <formulaList>
                                          <formula category="TIME_TO_WAIT_IN_SECONDS">
                                            <additionalChildren/>
                                            <type>NUMBER</type>
                                            <value>0.2</value>
                                          </formula>
                                        </formulaList>
                                      </brick>
                                      <brick type="SetLookBrick">
                                        <brickId>1371dfcd-ee80-41f1-8abe-6b15af249151</brickId>
                                        <commentedOut>false</commentedOut>
                                        <look reference="../../../../../../../../../lookList/look[4]"/>
                                      </brick>
                                      <brick type="ChangeVariableBrick">
                                        <brickId>a1d9ffb9-e018-43d9-b7ab-e6f0a35afcc2</brickId>
                                        <commentedOut>false</commentedOut>
                                        <formulaList>
                                          <formula category="VARIABLE_CHANGE">
                                            <additionalChildren/>
                                            <rightChild>
                                              <additionalChildren/>
                                              <type>NUMBER</type>
                                              <value>1</value>
                                            </rightChild>
                                            <type>OPERATOR</type>
                                            <value>MINUS</value>
                                          </formula>
                                        </formulaList>
                                        <userVariable reference="../../brick[2]/userVariable"/>
                                      </brick>
                                      <brick type="WaitBrick">
                                        <brickId>f6ae5c8f-4c41-44a8-9d36-107b6c8b3c18</brickId>
                                        <commentedOut>false</commentedOut>
                                        <formulaList>
                                          <formula category="TIME_TO_WAIT_IN_SECONDS">
                                            <additionalChildren/>
                                            <type>NUMBER</type>
                                            <value>0.2</value>
                                          </formula>
                                        </formulaList>
                                      </brick>
                                      <brick type="SetLookBrick">
                                        <brickId>2722ee3b-79b2-48de-8d51-24deb7fa62d1</brickId>
                                        <commentedOut>false</commentedOut>
                                        <look reference="../../../../../../../../../lookList/look[5]"/>
                                      </brick>
                                      <brick type="ChangeVariableBrick">
                                        <brickId>f34f368f-1986-4a1a-be5f-c845ec7d1a77</brickId>
                                        <commentedOut>false</commentedOut>
                                        <formulaList>
                                          <formula category="VARIABLE_CHANGE">
                                            <additionalChildren/>
                                            <rightChild>
                                              <additionalChildren/>
                                              <type>NUMBER</type>
                                              <value>1</value>
                                            </rightChild>
                                            <type>OPERATOR</type>
                                            <value>MINUS</value>
                                          </formula>
                                        </formulaList>
                                        <userVariable reference="../../brick[2]/userVariable"/>
                                      </brick>
                                      <brick type="WaitBrick">
                                        <brickId>b192a34d-023d-4c1a-b52b-ab190f6d9e1c</brickId>
                                        <commentedOut>false</commentedOut>
                                        <formulaList>
                                          <formula category="TIME_TO_WAIT_IN_SECONDS">
                                            <additionalChildren/>
                                            <type>NUMBER</type>
                                            <value>0.2</value>
                                          </formula>
                                        </formulaList>
                                      </brick>
                                      <brick type="SetLookBrick">
                                        <brickId>28dce1ee-50e5-4f9a-b50e-f8541e068c17</brickId>
                                        <commentedOut>false</commentedOut>
                                        <look reference="../../../../../../../../../lookList/look[6]"/>
                                      </brick>
                                      <brick type="ChangeVariableBrick">
                                        <brickId>87714013-b943-43ab-9690-54a3439ec6f5</brickId>
                                        <commentedOut>false</commentedOut>
                                        <formulaList>
                                          <formula category="VARIABLE_CHANGE">
                                            <additionalChildren/>
                                            <rightChild>
                                              <additionalChildren/>
                                              <type>NUMBER</type>
                                              <value>1</value>
                                            </rightChild>
                                            <type>OPERATOR</type>
                                            <value>MINUS</value>
                                          </formula>
                                        </formulaList>
                                        <userVariable reference="../../brick[2]/userVariable"/>
                                      </brick>
                                      <brick type="WaitBrick">
                                        <brickId>f13a3fab-9762-47e4-b267-a3dead5b7324</brickId>
                                        <commentedOut>false</commentedOut>
                                        <formulaList>
                                          <formula category="TIME_TO_WAIT_IN_SECONDS">
                                            <additionalChildren/>
                                            <type>NUMBER</type>
                                            <value>0.2</value>
                                          </formula>
                                        </formulaList>
                                      </brick>
                                      <brick type="SetLookBrick">
                                        <brickId>8103c31c-6267-4e4c-b65d-f03ef3292ba0</brickId>
                                        <commentedOut>false</commentedOut>
                                        <look reference="../../../../../../../../../lookList/look[7]"/>
                                      </brick>
                                      <brick type="ChangeVariableBrick">
                                        <brickId>bb44cda6-c3ca-4d65-9a42-88260eb1e437</brickId>
                                        <commentedOut>false</commentedOut>
                                        <formulaList>
                                          <formula category="VARIABLE_CHANGE">
                                            <additionalChildren/>
                                            <rightChild>
                                              <additionalChildren/>
                                              <type>NUMBER</type>
                                              <value>3</value>
                                            </rightChild>
                                            <type>OPERATOR</type>
                                            <value>MINUS</value>
                                          </formula>
                                        </formulaList>
                                        <userVariable reference="../../brick[2]/userVariable"/>
                                      </brick>
                                    </ifBranchBricks>
                                  </brick>
                                </loopBricks>
                              </brick>
                            </brickList>
                            <commentedOut>false</commentedOut>
                            <scriptId>d3238039-ae2e-400a-b37b-665996130c2e</scriptId>
                          </script>
                          <script type="BroadcastScript" posX="0.0" posY="0.0">
                            <brickList>
                              <brick type="HideBrick">
                                <brickId>7ece5d6a-c991-4818-8420-6c8bb0489d93</brickId>
                                <commentedOut>false</commentedOut>
                              </brick>
                            </brickList>
                            <commentedOut>false</commentedOut>
                            <scriptId>bfb85508-9bc3-4775-a06e-66e8616d39d9</scriptId>
                            <receivedMessage>Sumirvegeta</receivedMessage>
                          </script>
                          <script type="BroadcastScript" posX="0.0" posY="0.0">
                            <brickList>
                              <brick type="SetLookBrick">
                                <brickId>a33e8cb5-a87f-4f45-8f9c-f4a21dbdb802</brickId>
                                <commentedOut>false</commentedOut>
                                <look reference="../../../../../lookList/look[8]"/>
                              </brick>
                              <brick type="WaitBrick">
                                <brickId>d85434e5-142b-40c3-a45e-eb745a4d6108</brickId>
                                <commentedOut>false</commentedOut>
                                <formulaList>
                                  <formula category="TIME_TO_WAIT_IN_SECONDS">
                                    <additionalChildren/>
                                    <type>NUMBER</type>
                                    <value>0.3</value>
                                  </formula>
                                </formulaList>
                              </brick>
                              <brick type="SetLookBrick">
                                <brickId>7e703444-9dba-4eed-a736-e687786f4d92</brickId>
                                <commentedOut>false</commentedOut>
                                <look reference="../../../../../lookList/look[9]"/>
                              </brick>
                            </brickList>
                            <commentedOut>false</commentedOut>
                            <scriptId>eb464c77-0ea6-4eac-9f07-82a462907936</scriptId>
                            <receivedMessage>Morte vegeta</receivedMessage>
                          </script>
                        </scriptList>
                        <nfcTagList/>
                        <userVariables/>
                        <userLists/>
                        <userDefinedBrickList/>
                      </pointedObject>
                    </brick>
                    <brick type="SetRotationStyleBrick">
                      <brickId>f942a632-705d-43f3-ae64-08b02c3db796</brickId>
                      <commentedOut>false</commentedOut>
                      <selection>0</selection>
                    </brick>
                  </loopBricks>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>2c269791-debc-4fb0-936d-2c657c72a410</scriptId>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ChangeXByNBrick">
                  <brickId>1ab8494a-8caa-4497-853e-a97021152bef</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION_CHANGE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.5</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>a2cc3e7f-2511-4626-96d0-73ac8a31fd30</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[4]"/>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>a8ad32e4-5ad6-4669-8d8e-1b2a2ee569af</scriptId>
              <receivedMessage>Andar Direita</receivedMessage>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetLookBrick">
                  <brickId>988e7315-9f5a-467a-9768-1eb95a9a0a25</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look"/>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>d0389db7-8370-42fc-bca7-1f30c889884a</scriptId>
              <receivedMessage>Parar</receivedMessage>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ChangeXByNBrick">
                  <brickId>21293592-03c5-4813-9619-b3974fd6ed4d</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION_CHANGE">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>0.5</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>82163474-aa6a-4b68-ad8b-7633b0b20b8a</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[2]"/>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>86a27c67-29f1-4f0b-80b7-57107b2aca5c</scriptId>
              <receivedMessage>Andar Esquerda </receivedMessage>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetLookBrick">
                  <brickId>1c0183fe-67cf-44e9-a057-d19b321c21ed</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[5]"/>
                </brick>
                <brick type="WaitBrick">
                  <brickId>2621c045-0dd3-4986-b263-8ee81bf9c55c</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.1</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>ff0b0472-efa9-47ea-bf01-dd177ff7a248</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[6]"/>
                </brick>
                <brick type="WaitBrick">
                  <brickId>cf475568-106d-4ef7-b909-2922aa7d6e73</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.01</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>a99cf022-b1ed-4361-bd5b-3f3d10fa1381</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look"/>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>e0998d7f-5b0e-4c73-a6ec-10655264249b</scriptId>
              <receivedMessage>Soco</receivedMessage>
            </script>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ForeverBrick">
                  <brickId>8838b80a-0821-439f-8b58-d854251e2f35</brickId>
                  <commentedOut>true</commentedOut>
                  <loopBricks>
                    <brick type="IfThenLogicBeginBrick">
                      <brickId>86ec4197-74a5-42ea-8725-9d56625d13ec</brickId>
                      <commentedOut>true</commentedOut>
                      <formulaList>
                        <formula category="IF_CONDITION">
                          <additionalChildren/>
                          <leftChild>
                            <additionalChildren/>
                            <type>COLLISION_FORMULA</type>
                            <value>Vegeta</value>
                          </leftChild>
                          <rightChild>
                            <additionalChildren/>
                            <type>FUNCTION</type>
                            <value>TRUE</value>
                          </rightChild>
                          <type>OPERATOR</type>
                          <value>EQUAL</value>
                        </formula>
                      </formulaList>
                      <ifBranchBricks>
                        <brick type="ChangeVariableBrick">
                          <brickId>623ff3f6-e205-4f8c-b720-aad30beb9050</brickId>
                          <commentedOut>true</commentedOut>
                          <formulaList>
                            <formula category="VARIABLE_CHANGE">
                              <additionalChildren/>
                              <rightChild>
                                <additionalChildren/>
                                <type>NUMBER</type>
                                <value>1</value>
                              </rightChild>
                              <type>OPERATOR</type>
                              <value>MINUS</value>
                            </formula>
                          </formulaList>
                          <userVariable type="UserVariable" serialization="custom">
                            <userVariable>
                              <default>
                                <initialIndex>4</initialIndex>
                                <deviceValueKey>f01873b0-6bbe-4c1f-b639-7ca84593fb67</deviceValueKey>
                                <name>Vida_bot</name>
                              </default>
                            </userVariable>
                          </userVariable>
                        </brick>
                        <brick type="WaitBrick">
                          <brickId>17f9c31d-18f7-4bbb-b1d3-8e2be616b611</brickId>
                          <commentedOut>true</commentedOut>
                          <formulaList>
                            <formula category="TIME_TO_WAIT_IN_SECONDS">
                              <additionalChildren/>
                              <type>NUMBER</type>
                              <value>0.2</value>
                            </formula>
                          </formulaList>
                        </brick>
                        <brick type="ChangeVariableBrick">
                          <brickId>f77a4ed2-7176-48af-9efd-dcae01a2acb7</brickId>
                          <commentedOut>true</commentedOut>
                          <formulaList>
                            <formula category="VARIABLE_CHANGE">
                              <additionalChildren/>
                              <rightChild>
                                <additionalChildren/>
                                <type>NUMBER</type>
                                <value>1</value>
                              </rightChild>
                              <type>OPERATOR</type>
                              <value>MINUS</value>
                            </formula>
                          </formulaList>
                          <userVariable reference="../../brick/userVariable"/>
                        </brick>
                        <brick type="WaitBrick">
                          <brickId>7814f3a2-2b88-4c3d-94d9-1fa6b8bbcc47</brickId>
                          <commentedOut>true</commentedOut>
                          <formulaList>
                            <formula category="TIME_TO_WAIT_IN_SECONDS">
                              <additionalChildren/>
                              <type>NUMBER</type>
                              <value>0.2</value>
                            </formula>
                          </formulaList>
                        </brick>
                        <brick type="ChangeVariableBrick">
                          <brickId>484f0570-7f66-4fb6-a92b-852486ca5a62</brickId>
                          <commentedOut>true</commentedOut>
                          <formulaList>
                            <formula category="VARIABLE_CHANGE">
                              <additionalChildren/>
                              <rightChild>
                                <additionalChildren/>
                                <type>NUMBER</type>
                                <value>1</value>
                              </rightChild>
                              <type>OPERATOR</type>
                              <value>MINUS</value>
                            </formula>
                          </formulaList>
                          <userVariable reference="../../brick/userVariable"/>
                        </brick>
                        <brick type="WaitBrick">
                          <brickId>d7d5650b-9846-42d0-b7a5-dcc9afd11da0</brickId>
                          <commentedOut>true</commentedOut>
                          <formulaList>
                            <formula category="TIME_TO_WAIT_IN_SECONDS">
                              <additionalChildren/>
                              <type>NUMBER</type>
                              <value>0.2</value>
                            </formula>
                          </formulaList>
                        </brick>
                        <brick type="ChangeVariableBrick">
                          <brickId>40295e9a-dba4-4e82-a2f6-73fbe2af7ad3</brickId>
                          <commentedOut>true</commentedOut>
                          <formulaList>
                            <formula category="VARIABLE_CHANGE">
                              <additionalChildren/>
                              <rightChild>
                                <additionalChildren/>
                                <type>NUMBER</type>
                                <value>1</value>
                              </rightChild>
                              <type>OPERATOR</type>
                              <value>MINUS</value>
                            </formula>
                          </formulaList>
                          <userVariable reference="../../brick/userVariable"/>
                        </brick>
                        <brick type="WaitBrick">
                          <brickId>fc930d82-94b9-4d04-a79b-34c86ae5502e</brickId>
                          <commentedOut>true</commentedOut>
                          <formulaList>
                            <formula category="TIME_TO_WAIT_IN_SECONDS">
                              <additionalChildren/>
                              <type>NUMBER</type>
                              <value>0.2</value>
                            </formula>
                          </formulaList>
                        </brick>
                        <brick type="ChangeVariableBrick">
                          <brickId>a8492f8a-f4a5-4e47-955b-f0c81352c1d1</brickId>
                          <commentedOut>true</commentedOut>
                          <formulaList>
                            <formula category="VARIABLE_CHANGE">
                              <additionalChildren/>
                              <rightChild>
                                <additionalChildren/>
                                <type>NUMBER</type>
                                <value>1</value>
                              </rightChild>
                              <type>OPERATOR</type>
                              <value>MINUS</value>
                            </formula>
                          </formulaList>
                          <userVariable reference="../../brick/userVariable"/>
                        </brick>
                      </ifBranchBricks>
                    </brick>
                  </loopBricks>
                </brick>
              </brickList>
              <commentedOut>true</commentedOut>
              <scriptId>23c96043-5387-4412-9122-93f6f36898ba</scriptId>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetLookBrick">
                  <brickId>1fc16a9b-ccd1-4f8c-92cb-0e72e4e2f1d9</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[7]"/>
                </brick>
                <brick type="WaitBrick">
                  <brickId>d32a916c-c4d8-4b7d-95f2-90b1425293d5</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.3</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>99438a29-5613-4889-9f25-f54fc22825e8</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look"/>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>a4bc0d38-f493-4b48-bb39-5920ef83b674</scriptId>
              <receivedMessage>Kibast</receivedMessage>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetLookBrick">
                  <brickId>bd8f9e5f-b0b3-4450-9802-8a8d530f7153</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[8]"/>
                </brick>
                <brick type="WaitBrick">
                  <brickId>4504fee7-56db-4b57-a121-cad80d87a874</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.5</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>35565548-bdb0-42c4-924b-e61df52d1ab7</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[9]"/>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>b18ec0fe-bf72-41a6-a410-a9db1e3c8ad0</scriptId>
              <receivedMessage>Mortegoku</receivedMessage>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="HideBrick">
                  <brickId>2d0ee2c0-b6db-4226-99f7-4d2deb2635d5</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>d5631fce-3015-4e62-b75b-da31237f4a60</scriptId>
              <receivedMessage>Sumir goku</receivedMessage>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetLookBrick">
                  <brickId>2b120a21-5fda-4049-833e-13bef809e2b0</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[7]"/>
                </brick>
                <brick type="WaitBrick">
                  <brickId>d6689032-9c65-4a1d-ad01-14a2ade8b12a</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.1</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>8f9ef80e-b4e1-42dc-8dfe-03abf256fc3c</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look"/>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>2c15d6da-3d90-4fec-a78a-3b319a543a06</scriptId>
              <receivedMessage>Gamehameha</receivedMessage>
            </script>
            <script type="WhenConditionScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ChangeXByNBrick">
                  <brickId>d5855fe4-488a-4c38-9826-9e3337959e21</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION_CHANGE">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>10</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>b3d473a3-61b7-4ffa-955b-c4e142ca2bc8</scriptId>
              <formulaMap>
                <formula category="IF_CONDITION">
                  <additionalChildren/>
                  <leftChild>
                    <additionalChildren/>
                    <type>COLLISION_FORMULA</type>
                    <value>Barreira </value>
                  </leftChild>
                  <rightChild>
                    <additionalChildren/>
                    <type>FUNCTION</type>
                    <value>TRUE</value>
                  </rightChild>
                  <type>OPERATOR</type>
                  <value>EQUAL</value>
                </formula>
              </formulaMap>
            </script>
            <script type="WhenConditionScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ChangeXByNBrick">
                  <brickId>1eea94db-1ea9-4864-9b4a-b167a34c421b</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION_CHANGE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>10</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>ae0d66e9-12be-44e5-b6f3-2e3253593316</scriptId>
              <formulaMap>
                <formula category="IF_CONDITION">
                  <additionalChildren/>
                  <leftChild>
                    <additionalChildren/>
                    <type>COLLISION_FORMULA</type>
                    <value>Barreira  (1)</value>
                  </leftChild>
                  <rightChild>
                    <additionalChildren/>
                    <type>FUNCTION</type>
                    <value>TRUE</value>
                  </rightChild>
                  <type>OPERATOR</type>
                  <value>EQUAL</value>
                </formula>
              </formulaMap>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object reference="../object[4]/scriptList/script/brickList/brick[4]/loopBricks/brick/pointedObject"/>
        <object type="Sprite" name="&#xa;Soco">
          <lookList>
            <look fileName="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d_#1.png" name="&#xa;Soco">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>132a2fbb-da60-43c2-a70f-70faeb34efa3</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>1088</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>460</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>37fd7ee1-d6f0-4ef8-9297-d9287839814d</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>600</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>e4bf480a-8132-4e15-8f6e-0d0b14127d32</scriptId>
            </script>
            <script type="WhenScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetSizeToBrick">
                  <brickId>158a152d-45de-4b69-b200-4345384a7fb5</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>500</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="WaitBrick">
                  <brickId>528db652-2bcb-431c-8008-ea0128c92cd2</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.2</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>97cfefc7-d71f-49e8-ba0a-950fe48b0311</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>600</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="BroadcastBrick">
                  <brickId>00d0bd53-c1ff-4a90-af5a-fd7f634149c5</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Soco</broadcastMessage>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>e7b89fa2-f191-4725-9ad4-1ada3bf353b6</scriptId>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="HideBrick">
                  <brickId>34cd5cbf-5afb-43e4-9049-06ff39527a00</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>bf86541d-5ba3-41dc-a6b5-0fef88661c9d</scriptId>
              <receivedMessage>Mortegoku</receivedMessage>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Vida goku">
          <lookList>
            <look fileName="imagesss (2)_#0.png" name="Vida 1">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="imagesss (2)_#1.png" name="Vida 2">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="imagesss (2)_#2.png" name="Vida 3">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="imagesss (2)_#4.png" name="Vida 4">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="imagesss (2)_#3.png" name="Vida 5">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="imagesss (2)_#5.png" name="Vida 6">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>64fd111c-3057-4321-ad28-5be43f4e5c3d</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>769</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>451</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>58d8a841-9438-457e-bd94-ed07aea635f8</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>400</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetVariableBrick">
                  <brickId>04cdcdee-35f3-4dae-a2a9-2f602dde19e7</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="VARIABLE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>100</value>
                    </formula>
                  </formulaList>
                  <userVariable reference="../../../../../../object[4]/scriptList/script/brickList/brick[4]/loopBricks/brick/pointedObject/scriptList/script[4]/brickList/brick/loopBricks/brick/ifBranchBricks/brick[2]/userVariable"/>
                </brick>
                <brick type="ShowTextBrick">
                  <brickId>dc9a2b35-5259-4355-b703-86ce76083e8f</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>400</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>571</value>
                    </formula>
                  </formulaList>
                  <userVariable reference="../../../../../../object[4]/scriptList/script/brickList/brick[4]/loopBricks/brick/pointedObject/scriptList/script[4]/brickList/brick/loopBricks/brick/ifBranchBricks/brick[2]/userVariable"/>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>92f1b7e8-411d-46dc-b942-15e9f480c0b1</scriptId>
            </script>
            <script type="WhenConditionScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="BroadcastBrick">
                  <brickId>5ed92614-1000-4964-90df-030182452e81</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Sumirvegeta</broadcastMessage>
                </brick>
                <brick type="BroadcastBrick">
                  <brickId>144e7ba8-91be-4168-bf73-11726de1f4b9</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Mortegoku</broadcastMessage>
                </brick>
                <brick type="WaitBrick">
                  <brickId>5c118305-a605-4dbc-abb5-a7884f71766b</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>3</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SceneStartBrick">
                  <brickId>a95a3b0f-2466-45a9-9f4f-be139b0c3ede</brickId>
                  <commentedOut>false</commentedOut>
                  <sceneToStart>Escolha De Personagem</sceneToStart>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>d3eaa73d-2c43-41c4-bbb9-9232885f1e6a</scriptId>
              <formulaMap>
                <formula category="IF_CONDITION">
                  <additionalChildren/>
                  <leftChild>
                    <additionalChildren/>
                    <type>USER_VARIABLE</type>
                    <value>Vida_Goku</value>
                  </leftChild>
                  <rightChild>
                    <additionalChildren/>
                    <rightChild>
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>1</value>
                    </rightChild>
                    <type>OPERATOR</type>
                    <value>MINUS</value>
                  </rightChild>
                  <type>OPERATOR</type>
                  <value>SMALLER_THAN</value>
                </formula>
              </formulaMap>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Vida bot">
          <lookList>
            <look fileName="imagesss (2)_#6.png" name="Vida 1">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="imagesss (2)_#7.png" name="Vida 2">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="imagesss (2)_#8.png" name="Vida 3">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="imagesss (2)_#9.png" name="Vida 4">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="imagesss (2)_#10.png" name="Vida 5">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="imagesss (2)_#11.png" name="Vida 6">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>ed31c2be-2ce8-4b6d-aa73-f44793bb8811</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>770</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>440</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>908db4b6-6e90-4779-8b1a-f82b3d36cdd8</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>400</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetVariableBrick">
                  <brickId>5bc855a2-befe-42d8-99d3-6741c522007e</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="VARIABLE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>100</value>
                    </formula>
                  </formulaList>
                  <userVariable reference="../../../../../../object[4]/scriptList/script[6]/brickList/brick/loopBricks/brick/ifBranchBricks/brick/userVariable"/>
                </brick>
                <brick type="ShowTextBrick">
                  <brickId>e2529cd8-3551-4bde-901a-bdcbecb89a2f</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>400</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>571</value>
                    </formula>
                  </formulaList>
                  <userVariable reference="../../../../../../object[4]/scriptList/script[6]/brickList/brick/loopBricks/brick/ifBranchBricks/brick/userVariable"/>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>cd7531cb-e462-433c-b78b-5019ca39ee43</scriptId>
            </script>
            <script type="WhenConditionScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="BroadcastBrick">
                  <brickId>6392d527-466d-45be-8685-e6ad5959b7de</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Morte vegeta</broadcastMessage>
                </brick>
                <brick type="BroadcastBrick">
                  <brickId>04e251cb-71fc-4b27-afa3-6825beff45fc</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Sumir goku</broadcastMessage>
                </brick>
                <brick type="WaitBrick">
                  <brickId>64898112-556f-482d-9ed0-f852d596941a</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>3</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="ExitStageBrick">
                  <brickId>abad6fd9-4828-454f-bf3c-b7637ab3f1be</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
                <brick type="SceneStartBrick">
                  <brickId>e3fcae0e-3219-4ef1-9340-016a76bdefad</brickId>
                  <commentedOut>false</commentedOut>
                  <sceneToStart>Game over</sceneToStart>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>af2ec3db-7738-4cc8-960e-e6911202dc5c</scriptId>
              <formulaMap>
                <formula category="IF_CONDITION">
                  <additionalChildren/>
                  <leftChild>
                    <additionalChildren/>
                    <type>USER_VARIABLE</type>
                    <value>Vida_bot</value>
                  </leftChild>
                  <rightChild>
                    <additionalChildren/>
                    <rightChild>
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>1</value>
                    </rightChild>
                    <type>OPERATOR</type>
                    <value>MINUS</value>
                  </rightChild>
                  <type>OPERATOR</type>
                  <value>SMALLER_THAN</value>
                </formula>
              </formulaMap>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Imagem da vida goku">
          <lookList>
            <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#5.png" name="Imagem da vida goku">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>3c860c3c-5693-4c67-9040-6ccc307203de</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>1071</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>449</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>a22f5fc0-a7b5-4492-b5ed-52b2da087f0f</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>250</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>df7c1694-6995-4c73-b81e-2416c707385e</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Botão Ki">
          <lookList>
            <look fileName="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d_#2.png" name="Botão Ki">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d_#3.png" name="Botão Ki (1)">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>2d83f7cc-b319-45c7-b595-62d3a7d570e3</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>900</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>464</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>6a168688-7a88-44a0-b814-43b51579d74d</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>600</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>da2e0ce0-4a69-4326-a82b-10ca93ba0e26</scriptId>
            </script>
            <script type="WhenScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="BroadcastBrick">
                  <brickId>0f22baa4-89e9-480b-8400-ef488fc4c981</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Kibast</broadcastMessage>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>50fb6877-d905-46da-8a6c-f7433d64c03d</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>500</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="WaitBrick">
                  <brickId>5b3ca5fc-7a77-462a-b9aa-b10e53ef1405</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.2</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>b356a0bb-55f9-4594-bf0c-9acbf058d316</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>600</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="HideBrick">
                  <brickId>cc17f1c3-6534-47b6-9c46-4ff020d49498</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
                <brick type="WaitBrick">
                  <brickId>e61b13c7-4bb8-421a-9f59-4da4e376d965</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>3</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="ShowBrick">
                  <brickId>d7f36fa1-f4b3-4d92-8cb2-e57fc2309018</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>572a1594-83c7-4950-841f-6744e90ecbf3</scriptId>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="HideBrick">
                  <brickId>e05b1977-9605-46ef-a597-28f8264ee9c6</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>d694a81d-8718-4729-8edf-6c3386fef71a</scriptId>
              <receivedMessage>Mortegoku</receivedMessage>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Hitsoco">
          <lookList>
            <look fileName="Meu ator ou objeto.png" name="Hitsoco">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetTransparencyBrick">
                  <brickId>934db1e2-5bd4-4b9d-8bd6-34423e07dae2</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TRANSPARENCY">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>80</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="HideBrick">
                  <brickId>e2b7515b-e62a-48c2-bb3a-a49ce5fb9e72</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>218de4ff-11a8-42a7-895d-501c239eb7ae</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>500</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="ForeverBrick">
                  <brickId>b87207e3-5cd0-47b2-a8b9-6cf5ca284852</brickId>
                  <commentedOut>false</commentedOut>
                  <loopBricks>
                    <brick type="GoToBrick">
                      <brickId>ce3c780c-2856-4e83-b086-a77c8666f761</brickId>
                      <commentedOut>false</commentedOut>
                      <destinationSprite reference="../../../../../../../../object[4]"/>
                      <spinnerSelection>82</spinnerSelection>
                    </brick>
                  </loopBricks>
                </brick>
                <brick type="SetXBrick">
                  <brickId>7aa2b4e8-3ff9-41d3-91d4-c26728147e70</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>50</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>93042edd-0951-4986-b11a-90ae4d9de2f5</scriptId>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ShowBrick">
                  <brickId>cf7cd4c1-5003-4abd-869d-03fd1573604c</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
                <brick type="WaitBrick">
                  <brickId>f6173570-21e3-4ccf-81c1-fa259ba7cbff</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.2</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="HideBrick">
                  <brickId>c060ee46-2d05-4b52-b8d9-5af6a1e7297e</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>0cd6900a-9206-49a9-a13f-7d2008b41a17</scriptId>
              <receivedMessage>Soco</receivedMessage>
            </script>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ForeverBrick">
                  <brickId>7f9f0a48-4ced-4b68-b0da-cf6b1490b016</brickId>
                  <commentedOut>false</commentedOut>
                  <loopBricks>
                    <brick type="IfThenLogicBeginBrick">
                      <brickId>69b918d5-08e7-4244-8088-c7675183b125</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="IF_CONDITION">
                          <additionalChildren/>
                          <leftChild>
                            <additionalChildren/>
                            <type>COLLISION_FORMULA</type>
                            <value>Vegeta</value>
                          </leftChild>
                          <rightChild>
                            <additionalChildren/>
                            <type>FUNCTION</type>
                            <value>TRUE</value>
                          </rightChild>
                          <type>OPERATOR</type>
                          <value>EQUAL</value>
                        </formula>
                      </formulaList>
                      <ifBranchBricks>
                        <brick type="SetLookBrick">
                          <brickId>06d57d23-9921-4e78-bec8-039660573f4e</brickId>
                          <commentedOut>false</commentedOut>
                          <look reference="../../../../../../../../../lookList/look"/>
                        </brick>
                        <brick type="ChangeVariableBrick">
                          <brickId>fdf35733-132b-4c3f-aaf7-d9cde407c6ca</brickId>
                          <commentedOut>false</commentedOut>
                          <formulaList>
                            <formula category="VARIABLE_CHANGE">
                              <additionalChildren/>
                              <rightChild>
                                <additionalChildren/>
                                <type>NUMBER</type>
                                <value>1</value>
                              </rightChild>
                              <type>OPERATOR</type>
                              <value>MINUS</value>
                            </formula>
                          </formulaList>
                          <userVariable reference="../../../../../../../../../../object[4]/scriptList/script[6]/brickList/brick/loopBricks/brick/ifBranchBricks/brick/userVariable"/>
                        </brick>
                        <brick type="WaitBrick">
                          <brickId>b6e024be-fd51-4bbb-a972-7ad6b1580c60</brickId>
                          <commentedOut>false</commentedOut>
                          <formulaList>
                            <formula category="TIME_TO_WAIT_IN_SECONDS">
                              <additionalChildren/>
                              <type>NUMBER</type>
                              <value>0.2</value>
                            </formula>
                          </formulaList>
                        </brick>
                        <brick type="SetLookBrick">
                          <brickId>5029aee2-31d4-440e-9d44-c169d87cdc93</brickId>
                          <commentedOut>false</commentedOut>
                          <look reference="../../../../../../../../../lookList/look"/>
                        </brick>
                        <brick type="ChangeVariableBrick">
                          <brickId>36e9fbf9-4b47-4e2a-b526-81078896ba92</brickId>
                          <commentedOut>false</commentedOut>
                          <formulaList>
                            <formula category="VARIABLE_CHANGE">
                              <additionalChildren/>
                              <rightChild>
                                <additionalChildren/>
                                <type>NUMBER</type>
                                <value>1</value>
                              </rightChild>
                              <type>OPERATOR</type>
                              <value>MINUS</value>
                            </formula>
                          </formulaList>
                          <userVariable reference="../../../../../../../../../../object[4]/scriptList/script[6]/brickList/brick/loopBricks/brick/ifBranchBricks/brick/userVariable"/>
                        </brick>
                        <brick type="WaitBrick">
                          <brickId>b62ddd78-7aa4-4caf-878a-ad8ab56f9725</brickId>
                          <commentedOut>false</commentedOut>
                          <formulaList>
                            <formula category="TIME_TO_WAIT_IN_SECONDS">
                              <additionalChildren/>
                              <type>NUMBER</type>
                              <value>0.2</value>
                            </formula>
                          </formulaList>
                        </brick>
                        <brick type="SetLookBrick">
                          <brickId>ecebfc4e-f777-4d49-bb9c-a8e012068540</brickId>
                          <commentedOut>false</commentedOut>
                          <look reference="../../../../../../../../../lookList/look"/>
                        </brick>
                        <brick type="ChangeVariableBrick">
                          <brickId>026b75e5-1624-403b-a807-635dd10c2800</brickId>
                          <commentedOut>false</commentedOut>
                          <formulaList>
                            <formula category="VARIABLE_CHANGE">
                              <additionalChildren/>
                              <rightChild>
                                <additionalChildren/>
                                <type>NUMBER</type>
                                <value>1</value>
                              </rightChild>
                              <type>OPERATOR</type>
                              <value>MINUS</value>
                            </formula>
                          </formulaList>
                          <userVariable reference="../../../../../../../../../../object[4]/scriptList/script[6]/brickList/brick/loopBricks/brick/ifBranchBricks/brick/userVariable"/>
                        </brick>
                        <brick type="WaitBrick">
                          <brickId>f5fc97e9-2d6d-4c15-a639-4ea2e6e51394</brickId>
                          <commentedOut>false</commentedOut>
                          <formulaList>
                            <formula category="TIME_TO_WAIT_IN_SECONDS">
                              <additionalChildren/>
                              <type>NUMBER</type>
                              <value>0.2</value>
                            </formula>
                          </formulaList>
                        </brick>
                        <brick type="SetLookBrick">
                          <brickId>adebe78a-aba9-41e5-bde7-0dfc398f8740</brickId>
                          <commentedOut>false</commentedOut>
                          <look reference="../../../../../../../../../lookList/look"/>
                        </brick>
                      </ifBranchBricks>
                    </brick>
                  </loopBricks>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>1aff26c4-2849-4e77-94ef-83c57a4e5394</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Kiblast">
          <lookList>
            <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#6.png" name="Kiblast">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#7.png" name="Kiblast (1)">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#8.png" name="Kiblast (2)">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#9.png" name="Kiblast (3)">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>e07e052d-ed4b-440e-b994-9aadba6878ef</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>134</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>640</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>527d60a9-a462-47d6-9471-d523342a3f82</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>300</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="HideBrick">
                  <brickId>28afd968-d906-4382-8f03-66affceadbb9</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>2fbc9962-6af0-463b-8806-08e6c2a74dd2</scriptId>
            </script>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ForeverBrick">
                  <brickId>e07da783-69f2-406a-a2a2-d47e8879836e</brickId>
                  <commentedOut>false</commentedOut>
                  <loopBricks>
                    <brick type="IfThenLogicBeginBrick">
                      <brickId>1904736a-8330-4ffc-bc11-2dc17bcdc828</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="IF_CONDITION">
                          <additionalChildren/>
                          <leftChild>
                            <additionalChildren/>
                            <type>COLLISION_FORMULA</type>
                            <value>Vegeta</value>
                          </leftChild>
                          <rightChild>
                            <additionalChildren/>
                            <type>FUNCTION</type>
                            <value>TRUE</value>
                          </rightChild>
                          <type>OPERATOR</type>
                          <value>EQUAL</value>
                        </formula>
                      </formulaList>
                      <ifBranchBricks>
                        <brick type="ChangeVariableBrick">
                          <brickId>7bb3f0c0-3073-4992-9322-20a791932f52</brickId>
                          <commentedOut>false</commentedOut>
                          <formulaList>
                            <formula category="VARIABLE_CHANGE">
                              <additionalChildren/>
                              <rightChild>
                                <additionalChildren/>
                                <type>NUMBER</type>
                                <value>5</value>
                              </rightChild>
                              <type>OPERATOR</type>
                              <value>MINUS</value>
                            </formula>
                          </formulaList>
                          <userVariable reference="../../../../../../../../../../object[4]/scriptList/script[6]/brickList/brick/loopBricks/brick/ifBranchBricks/brick/userVariable"/>
                        </brick>
                        <brick type="ShowBrick">
                          <brickId>780580bf-43c0-4a9f-b3d9-dc77fb4e9c2e</brickId>
                          <commentedOut>true</commentedOut>
                        </brick>
                        <brick type="HideBrick">
                          <brickId>604d6348-82ce-4130-aa48-75100f822782</brickId>
                          <commentedOut>false</commentedOut>
                        </brick>
                      </ifBranchBricks>
                    </brick>
                  </loopBricks>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>b31b7c26-e2dd-466e-804c-627d573aac03</scriptId>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetLookBrick">
                  <brickId>3637b864-a063-4655-9c7e-8f913aa01cc2</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look"/>
                </brick>
                <brick type="WaitBrick">
                  <brickId>570ba847-0571-477e-984d-7eb96a7a40ed</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.1</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>ed92872e-f1bd-4e0d-9efa-c9a78b93166a</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[2]"/>
                </brick>
                <brick type="WaitBrick">
                  <brickId>b0de95fd-bb7b-48ae-86e5-ffe54ba7b567</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.02</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>9741cafd-6470-4947-92f7-d3bff289e9c9</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[3]"/>
                </brick>
                <brick type="WaitBrick">
                  <brickId>baf22527-a86e-4771-968c-6a3f32b70d1d</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.02</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>db41ba1d-7a19-4ab2-b1fa-e4fc11f92dda</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[4]"/>
                </brick>
                <brick type="ShowBrick">
                  <brickId>4aac482d-a9ac-4423-86c0-a9b1a1552076</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
                <brick type="GoToBrick">
                  <brickId>7c939a25-b4dc-42cd-93bb-011f43ca59a1</brickId>
                  <commentedOut>false</commentedOut>
                  <destinationSprite reference="../../../../../../object[4]"/>
                  <spinnerSelection>82</spinnerSelection>
                </brick>
                <brick type="PointToBrick">
                  <brickId>cf15dc4c-5faf-493d-903a-ab8f79b0d334</brickId>
                  <commentedOut>false</commentedOut>
                  <pointedObject reference="../../../../../../object[4]/scriptList/script/brickList/brick[4]/loopBricks/brick/pointedObject"/>
                </brick>
                <brick type="RepeatBrick">
                  <brickId>85cf9afb-da34-4db8-9fae-af6f30baf0c8</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIMES_TO_REPEAT">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>90</value>
                    </formula>
                  </formulaList>
                  <loopBricks>
                    <brick type="MoveNStepsBrick">
                      <brickId>96b1d644-a497-4b0b-abc1-46fa59d6264b</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="STEPS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>20</value>
                        </formula>
                      </formulaList>
                    </brick>
                  </loopBricks>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>0bb4ea00-3fa3-4302-affa-f8753f37762e</scriptId>
              <receivedMessage>Kibast</receivedMessage>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Botão Gamehameha">
          <lookList>
            <look fileName="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d_#4.png" name="Gamehameha">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>87f4b784-ffd3-48b8-908d-17231b0ecff2</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>719</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>465</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>f8e3e02f-06a1-4015-a665-3aa0e0341652</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>600</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>a2716282-06ce-48b5-a31b-5c94c3d1e3c4</scriptId>
            </script>
            <script type="WhenScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="BroadcastBrick">
                  <brickId>516d30e2-4b3b-4f5f-bfed-97e7d0c5d38f</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Gamehameha</broadcastMessage>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>c50ceba9-b3ec-43dd-acb4-98c829929edb</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>500</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="WaitBrick">
                  <brickId>467ff68b-ff52-493d-b227-0735cdbf8ee6</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.2</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>52b69a6d-0ba6-4d83-8132-ab7e8699f8eb</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>600</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="HideBrick">
                  <brickId>f1056cd9-14c5-4924-a331-396f85d47f8e</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
                <brick type="WaitBrick">
                  <brickId>3e1cc33e-7821-4b1c-9528-57f3b8bb9c1d</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>5</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="ShowBrick">
                  <brickId>d090d8d7-fb36-4ff9-8b2f-9c1362c86f8c</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>f3cab106-89f9-481d-895c-f3571cd37e60</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Gamehameha">
          <lookList>
            <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#13.png" name="Gamehameha">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#14.png" name="Gamehameha (1)">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#15.png" name="Gamehameha (2)">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#16.png" name="Gamehameha (3)">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ForeverBrick">
                  <brickId>cb361984-bc82-4c8b-8336-9eda2069efc3</brickId>
                  <commentedOut>false</commentedOut>
                  <loopBricks>
                    <brick type="IfThenLogicBeginBrick">
                      <brickId>5e798814-8c7a-4fc4-afc1-748a660078a1</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="IF_CONDITION">
                          <additionalChildren/>
                          <leftChild>
                            <additionalChildren/>
                            <type>COLLISION_FORMULA</type>
                            <value>Vegeta</value>
                          </leftChild>
                          <rightChild>
                            <additionalChildren/>
                            <type>FUNCTION</type>
                            <value>TRUE</value>
                          </rightChild>
                          <type>OPERATOR</type>
                          <value>EQUAL</value>
                        </formula>
                      </formulaList>
                      <ifBranchBricks>
                        <brick type="ChangeVariableBrick">
                          <brickId>48987a06-0937-441a-a3dc-c28f63b00aa6</brickId>
                          <commentedOut>false</commentedOut>
                          <formulaList>
                            <formula category="VARIABLE_CHANGE">
                              <additionalChildren/>
                              <rightChild>
                                <additionalChildren/>
                                <type>NUMBER</type>
                                <value>10</value>
                              </rightChild>
                              <type>OPERATOR</type>
                              <value>MINUS</value>
                            </formula>
                          </formulaList>
                          <userVariable reference="../../../../../../../../../../object[4]/scriptList/script[6]/brickList/brick/loopBricks/brick/ifBranchBricks/brick/userVariable"/>
                        </brick>
                        <brick type="ShowBrick">
                          <brickId>583fd6b6-182b-4e4a-a642-e6cb015754c1</brickId>
                          <commentedOut>true</commentedOut>
                        </brick>
                        <brick type="HideBrick">
                          <brickId>0012689b-fa8a-4e7b-b7b9-80e69ea8f026</brickId>
                          <commentedOut>false</commentedOut>
                        </brick>
                      </ifBranchBricks>
                    </brick>
                  </loopBricks>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>3cd4b359-4ae5-44ad-9087-bedf5fa6fa90</scriptId>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ShowBrick">
                  <brickId>8f1e5d59-4fd4-4f63-a315-c253a2c520b8</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
                <brick type="GoToBrick">
                  <brickId>9ecd59b7-9f1b-4a6e-a324-0e986a2f60e8</brickId>
                  <commentedOut>false</commentedOut>
                  <destinationSprite reference="../../../../../../object[4]"/>
                  <spinnerSelection>82</spinnerSelection>
                </brick>
                <brick type="PointToBrick">
                  <brickId>75d1b675-f9c8-4c89-8465-35301e794d92</brickId>
                  <commentedOut>false</commentedOut>
                  <pointedObject reference="../../../../../../object[4]/scriptList/script/brickList/brick[4]/loopBricks/brick/pointedObject"/>
                </brick>
                <brick type="RepeatBrick">
                  <brickId>f62b4052-c2dd-41a9-a9a5-9f68ff44c14c</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIMES_TO_REPEAT">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>90</value>
                    </formula>
                  </formulaList>
                  <loopBricks>
                    <brick type="MoveNStepsBrick">
                      <brickId>3fad4ab5-c32a-4c3f-ae55-2a36f0ae08c8</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="STEPS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>250</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetSizeToBrick">
                      <brickId>6d95a828-92fe-4f58-ba44-1260e10a145f</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="SIZE">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>350</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetLookBrick">
                      <brickId>a829b207-4353-464a-849e-55259c4e47a5</brickId>
                      <commentedOut>false</commentedOut>
                      <look reference="../../../../../../../lookList/look[2]"/>
                    </brick>
                    <brick type="WaitBrick">
                      <brickId>420deaab-f426-4592-bcb2-4fabdd25cb8a</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="TIME_TO_WAIT_IN_SECONDS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>0.1</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetSizeToBrick">
                      <brickId>bf8272e8-56d7-400d-826b-05aa66fa6ae5</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="SIZE">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>500</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetLookBrick">
                      <brickId>d55f2a9b-3fde-4e1d-9f48-d174bb34d671</brickId>
                      <commentedOut>false</commentedOut>
                      <look reference="../../../../../../../lookList/look[3]"/>
                    </brick>
                    <brick type="WaitBrick">
                      <brickId>86018e4f-7a34-4c51-a696-815577f9b8d8</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="TIME_TO_WAIT_IN_SECONDS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>0.2</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetSizeToBrick">
                      <brickId>1dcc0e1a-19f3-46bb-9da1-057e47eda177</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="SIZE">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>450</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetLookBrick">
                      <brickId>2f12daad-af10-4f57-b8fd-6fa566bd5b35</brickId>
                      <commentedOut>false</commentedOut>
                      <look reference="../../../../../../../lookList/look[4]"/>
                    </brick>
                  </loopBricks>
                </brick>
                <brick type="WaitBrick">
                  <brickId>d7c3f785-e579-4d22-83e4-6a8bec6f25ee</brickId>
                  <commentedOut>true</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.3</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>12cf7ea2-471a-4866-8b18-0414ceaaead1</brickId>
                  <commentedOut>true</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>500</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>ce2da9fc-9aa9-410d-9e93-44d05d313c37</scriptId>
              <receivedMessage>Gamehameha</receivedMessage>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Hitbox vegeta">
          <lookList>
            <look fileName="Meu ator ou objeto_#0.png" name="Hitbox vegeta">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="HideBrick">
                  <brickId>3882fda3-e3fe-4b6c-9cef-689a947e89ca</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
                <brick type="ForeverBrick">
                  <brickId>edac9134-fb84-40e5-9238-866e20bc6cfe</brickId>
                  <commentedOut>false</commentedOut>
                  <loopBricks>
                    <brick type="GoToBrick">
                      <brickId>0e3b4b8f-70a5-4c91-9f50-df1dab28cfad</brickId>
                      <commentedOut>false</commentedOut>
                      <spinnerSelection>80</spinnerSelection>
                    </brick>
                  </loopBricks>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>b7c8b638-b041-42d9-a84d-3aef18d0ecf0</scriptId>
            </script>
            <script type="WhenConditionScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="BroadcastBrick">
                  <brickId>af5eeaef-01f8-41af-88e2-34c5ef45bada</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Mortegoku</broadcastMessage>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>4f0334c3-d477-415d-9bab-ee2fbb7c0e81</scriptId>
              <formulaMap>
                <formula category="IF_CONDITION">
                  <additionalChildren/>
                  <leftChild>
                    <additionalChildren/>
                    <type>COLLISION_FORMULA</type>
                    <value>Goku</value>
                  </leftChild>
                  <rightChild>
                    <additionalChildren/>
                    <type>FUNCTION</type>
                    <value>TRUE</value>
                  </rightChild>
                  <type>OPERATOR</type>
                  <value>EQUAL</value>
                </formula>
              </formulaMap>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Barreira ">
          <lookList>
            <look fileName="Meu ator ou objeto_#1.png" name="Barreira ">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>6fac61b0-f120-4757-a69e-c6cfdc9b4ae7</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>1207</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>46</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>b922319e-cce8-497b-a161-9d6bd469ef28</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>90</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>a5253665-c943-4705-80fc-2b256cacc1a2</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Barreira  (1)">
          <lookList>
            <look fileName="Meu ator ou objeto_#2.png" name="Barreira ">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>85597fd6-e174-43cc-b23f-6d2a9fab023d</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>1210</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>3</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetTransparencyBrick">
                  <brickId>20cb57f1-2844-4893-af9c-86b6646c8a85</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TRANSPARENCY">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>90</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>fa979053-0322-48bf-b2b9-482897f01234</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Resetar">
          <lookList>
            <look fileName="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d_#5.png" name="Resetar">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>13ae6236-0b3c-4fb7-aecf-c1f836260a01</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>500</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>3b22a2fe-b78f-4b31-b795-3146348da027</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>500</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>a9d555e3-7ece-4adc-85fe-433fec6e4a1e</scriptId>
            </script>
            <script type="WhenScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SceneStartBrick">
                  <brickId>a3bbbe2d-414d-4753-a515-65128e244af4</brickId>
                  <commentedOut>false</commentedOut>
                  <sceneToStart>Cutscene</sceneToStart>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>2c10393a-451e-4ffa-a2d9-25f19b6c2d5f</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Ganhku">
          <lookList>
            <look fileName="Meu ator ou objeto_#3.png" name="Ganhku">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>388e785f-8015-40fa-a22b-451e406d9f07</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="HideBrick">
                  <brickId>dbbd6230-7fac-413d-8458-e9e87f6c74d8</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>193d69ff-d2d3-44bd-a9da-890ac557274b</scriptId>
            </script>
            <script type="WhenConditionScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ShowBrick">
                  <brickId>30e17683-72d8-4563-99b4-bcaf647083f2</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>b01a5714-c4de-40a1-87c0-c18d86815250</scriptId>
              <formulaMap>
                <formula category="IF_CONDITION">
                  <additionalChildren/>
                  <leftChild>
                    <additionalChildren/>
                    <type>USER_VARIABLE</type>
                    <value>Vida_bot</value>
                  </leftChild>
                  <rightChild>
                    <additionalChildren/>
                    <rightChild>
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>1</value>
                    </rightChild>
                    <type>OPERATOR</type>
                    <value>MINUS</value>
                  </rightChild>
                  <type>OPERATOR</type>
                  <value>SMALLER_THAN</value>
                </formula>
              </formulaMap>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
      </objectList>
    </scene>
    <scene>
      <name>Game over</name>
      <objectList>
        <object type="Sprite" name="Fundo">
          <lookList>
            <look fileName="dragon-ball-planet-vegeta-virtual-background-for-zoom.jpeg" name="dragon-ball-planet-vegeta-virtual-background-for-zoom">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetSizeToBrick">
                  <brickId>cde063a9-0195-4a7e-b495-2d92549acaaa</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>140</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>0a37dcba-5675-4a94-a53f-2cebe0402add</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Reniciar ">
          <lookList>
            <look fileName="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d.png" name="Reniciar ">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetSizeToBrick">
                  <brickId>2654471c-624f-4c9a-a13c-c4320ef0e58f</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>500</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="ForeverBrick">
                  <brickId>6aa02218-a1d3-4fa2-b62c-01ab43e37edc</brickId>
                  <commentedOut>false</commentedOut>
                  <loopBricks>
                    <brick type="GlideToBrick">
                      <brickId>2003dba4-08e4-46b5-9360-2c019f61add1</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="X_DESTINATION">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>0</value>
                        </formula>
                        <formula category="DURATION_IN_SECONDS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>1.0</value>
                        </formula>
                        <formula category="Y_DESTINATION">
                          <additionalChildren/>
                          <rightChild>
                            <additionalChildren/>
                            <type>NUMBER</type>
                            <value>100</value>
                          </rightChild>
                          <type>OPERATOR</type>
                          <value>MINUS</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="GlideToBrick">
                      <brickId>1fdc5955-2f85-4a2f-890f-8d5aeea69c20</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="X_DESTINATION">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>0</value>
                        </formula>
                        <formula category="DURATION_IN_SECONDS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>1.0</value>
                        </formula>
                        <formula category="Y_DESTINATION">
                          <additionalChildren/>
                          <rightChild>
                            <additionalChildren/>
                            <type>NUMBER</type>
                            <value>130</value>
                          </rightChild>
                          <type>OPERATOR</type>
                          <value>MINUS</value>
                        </formula>
                      </formulaList>
                    </brick>
                  </loopBricks>
                </brick>
                <brick type="PlaceAtBrick">
                  <brickId>46e146cb-6de2-4ffc-9a93-0daec2cd940a</brickId>
                  <commentedOut>true</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>39</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>5</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>24079456-4f45-42c3-828b-e61fa8231136</scriptId>
            </script>
            <script type="WhenScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="TurnLeftBrick">
                  <brickId>117d9b46-4f39-4f59-a57a-2cefc828cfb8</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TURN_LEFT_DEGREES">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>15.0</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="WaitBrick">
                  <brickId>dd6aa329-2b34-4c29-a6b9-9d0d0cc008ec</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.01</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="TurnRightSpeedBrick">
                  <brickId>07bb057c-69dc-4a57-a56e-3ef133207367</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="PHYSICS_TURN_RIGHT_SPEED">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>15</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="WaitBrick">
                  <brickId>e09b0599-575e-42f2-9c0b-e2b122cb804b</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.01</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SceneStartBrick">
                  <brickId>14777e75-3929-4a9e-876b-1a5dda425919</brickId>
                  <commentedOut>false</commentedOut>
                  <sceneToStart>Cena</sceneToStart>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>49927676-9572-4c90-9fb8-51d07cd5a57f</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
      </objectList>
    </scene>
    <scene>
      <name>Luta (1)</name>
      <objectList>
        <object type="Sprite" name="Fundo">
          <lookList/>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetSizeToBrick">
                  <brickId>9a971932-06b9-4034-b3c7-b55cf32f0d24</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>150</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>7e4eab51-9aae-448b-83c3-f2a9f43d7d1c</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="&#xa;Direita">
          <lookList/>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>a7354655-3899-419e-a7e5-5ed60cc20fb7</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>720</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>422</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>73b09fbf-51b5-4e93-a944-3ba0285fc7c2</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>700</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetTransparencyBrick">
                  <brickId>04d68e6d-8603-405c-97bb-2b74a86c9b87</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TRANSPARENCY">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>20</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>3789296b-7a73-42e8-8d33-cf873a86cd5b</scriptId>
            </script>
            <script type="WhenScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetTransparencyBrick">
                  <brickId>c22d57ad-1ba9-431e-a173-f41fe305ff89</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TRANSPARENCY">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>15</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="WaitBrick">
                  <brickId>625aa1e1-93ff-4091-a2e5-819d212be232</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.2</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetTransparencyBrick">
                  <brickId>1e57fe26-45d4-4183-8697-bf79a3089f19</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TRANSPARENCY">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>20</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="BroadcastBrick">
                  <brickId>9b1b6f0d-8783-4c0b-8397-7800a31c1622</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Andar Direita</broadcastMessage>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>bbbe35d5-ff4f-479d-b218-821b256a4d2b</scriptId>
            </script>
            <script type="WhenScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="RepeatUntilBrick">
                  <brickId>e710b2b9-0cd6-43be-a594-99a88db87bff</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="REPEAT_UNTIL_CONDITION">
                      <additionalChildren/>
                      <leftChild>
                        <additionalChildren/>
                        <type>SENSOR</type>
                        <value>FINGER_TOUCHED</value>
                      </leftChild>
                      <rightChild>
                        <additionalChildren/>
                        <type>FUNCTION</type>
                        <value>FALSE</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>EQUAL</value>
                    </formula>
                  </formulaList>
                  <loopBricks>
                    <brick type="BroadcastBrick">
                      <brickId>3627cb91-ed4b-4a60-9772-0980310e183c</brickId>
                      <commentedOut>false</commentedOut>
                      <broadcastMessage>Andar Direita</broadcastMessage>
                    </brick>
                  </loopBricks>
                </brick>
                <brick type="BroadcastBrick">
                  <brickId>e842a480-7275-43c5-8ca0-247eec8c70c7</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Parar</broadcastMessage>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>3c9817c6-9c36-4e1d-8ca9-3788afce4dda</scriptId>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="HideBrick">
                  <brickId>08e2cac7-44be-4b66-9fc9-e974f1149e80</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>01473615-78d4-4d91-be59-3f4833b0b64b</scriptId>
              <receivedMessage>Mortegoku</receivedMessage>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Esquerda ">
          <lookList/>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>5a0c937f-c214-41c8-9d3b-986962bba146</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>1064</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>420</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>3c207a8e-7420-4ce5-bf9b-e6a34d2ed140</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>700</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetTransparencyBrick">
                  <brickId>3fe6183f-6fbb-4cfa-bc3d-6b011c51e233</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TRANSPARENCY">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>20</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>09eb04b4-86da-43fa-85d3-da0123093ed4</scriptId>
            </script>
            <script type="WhenScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetTransparencyBrick">
                  <brickId>125e18cd-66c0-4284-8ccc-f78db9dc7ccb</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TRANSPARENCY">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>15</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="WaitBrick">
                  <brickId>9fcdcb94-bd32-4f8a-b522-01f320e940da</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.2</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetTransparencyBrick">
                  <brickId>59030806-5de6-4393-8c36-e5b3b24b40b6</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TRANSPARENCY">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>20</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="BroadcastBrick">
                  <brickId>f96c36ee-d335-4fb6-8e3e-78eee2f0cab8</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Andar Esquerda </broadcastMessage>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>4beeb8b5-9eb5-4b3e-904d-6da1f6484b21</scriptId>
            </script>
            <script type="WhenScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="RepeatUntilBrick">
                  <brickId>e17a36d5-671b-4887-abea-d225165bdeb0</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="REPEAT_UNTIL_CONDITION">
                      <additionalChildren/>
                      <leftChild>
                        <additionalChildren/>
                        <type>SENSOR</type>
                        <value>FINGER_TOUCHED</value>
                      </leftChild>
                      <rightChild>
                        <additionalChildren/>
                        <type>FUNCTION</type>
                        <value>FALSE</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>EQUAL</value>
                    </formula>
                  </formulaList>
                  <loopBricks>
                    <brick type="BroadcastBrick">
                      <brickId>1e469736-0610-4f7e-ab83-6d73fdf89446</brickId>
                      <commentedOut>false</commentedOut>
                      <broadcastMessage>Andar Esquerda </broadcastMessage>
                    </brick>
                  </loopBricks>
                </brick>
                <brick type="BroadcastBrick">
                  <brickId>7a772d6c-3280-4382-bee3-e30621bdf909</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Parar</broadcastMessage>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>1d3ba024-4116-4e38-bfd4-a5c0000acc10</scriptId>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="HideBrick">
                  <brickId>ecda2d5e-9d45-4b42-a1fb-38f9ee8355d4</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>e68ba11f-c343-4c25-9b80-7334b851eab9</scriptId>
              <receivedMessage>Mortegoku</receivedMessage>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Goku">
          <lookList/>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="IfOnEdgeBounceBrick">
                  <brickId>abfc2374-d838-4b69-9c2d-ec1c13e09d0e</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
                <brick type="PlaceAtBrick">
                  <brickId>41fda7c2-f70d-49e8-88af-bca178241240</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>1019</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>149</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>7db5e1a3-8efd-4fce-801d-5dba4e41d69a</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>550</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="ForeverBrick">
                  <brickId>6898611a-2475-4d17-820f-89d7cf745b26</brickId>
                  <commentedOut>false</commentedOut>
                  <loopBricks>
                    <brick type="PointToBrick">
                      <brickId>0be1a917-c25b-472e-8052-31bb31e8c3af</brickId>
                      <commentedOut>false</commentedOut>
                      <pointedObject reference="../../../../../../../../../../scene[4]/objectList/object[4]/scriptList/script/brickList/brick[4]/loopBricks/brick/pointedObject"/>
                    </brick>
                    <brick type="SetRotationStyleBrick">
                      <brickId>c99977af-2b33-4ebf-979c-aa324681feac</brickId>
                      <commentedOut>false</commentedOut>
                      <selection>0</selection>
                    </brick>
                  </loopBricks>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>548a6d6f-4fca-410e-8f93-40ab7ad97f06</scriptId>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ChangeXByNBrick">
                  <brickId>36a49dad-f04a-4129-a9ec-e93e6a24e868</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION_CHANGE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.5</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>ad16c4eb-63e3-4721-bd4c-d9df312a9518</brickId>
                  <commentedOut>false</commentedOut>
                  <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#1.png" name="Direita 2">
                    <isWebRequest>false</isWebRequest>
                    <valid>true</valid>
                  </look>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>bb94bde6-56a7-4266-af8f-ce2c5884e3c4</scriptId>
              <receivedMessage>Andar Direita</receivedMessage>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetLookBrick">
                  <brickId>dc68c1a0-a26d-4184-b92f-3d576457ff49</brickId>
                  <commentedOut>false</commentedOut>
                  <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#2.png" name="Parado">
                    <isWebRequest>false</isWebRequest>
                    <valid>true</valid>
                  </look>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>408353f1-3081-4758-8850-3f07bfcaa8c7</scriptId>
              <receivedMessage>Parar</receivedMessage>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ChangeXByNBrick">
                  <brickId>ff8aa9fc-3636-47a9-98c6-46022a8e1036</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION_CHANGE">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>0.5</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>a70d5d51-31e9-43d9-9f41-3468cb7a568f</brickId>
                  <commentedOut>false</commentedOut>
                  <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#0.png" name="Esquerda ">
                    <isWebRequest>false</isWebRequest>
                    <valid>true</valid>
                  </look>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>6faa17e2-0a24-4338-acc4-45318bc6ddc0</scriptId>
              <receivedMessage>Andar Esquerda </receivedMessage>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetLookBrick">
                  <brickId>667ab668-6dab-4dd3-840c-45338de1a765</brickId>
                  <commentedOut>false</commentedOut>
                  <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#3.png" name="Soco 1">
                    <isWebRequest>false</isWebRequest>
                    <valid>true</valid>
                  </look>
                </brick>
                <brick type="WaitBrick">
                  <brickId>86b4d6f5-1042-4073-afc6-84390117c92f</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.1</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>50655fca-82a2-4ca6-bf6d-a22bc2f9f9dd</brickId>
                  <commentedOut>false</commentedOut>
                  <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#4.png" name="Soco 2">
                    <isWebRequest>false</isWebRequest>
                    <valid>true</valid>
                  </look>
                </brick>
                <brick type="WaitBrick">
                  <brickId>d569f0b9-95b3-4884-a290-d61b57faad14</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.01</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>093c9467-e3e6-4faa-acbd-247b01fa0280</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../script[3]/brickList/brick/look"/>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>69693ead-d107-44bf-8082-edb0903e8fa0</scriptId>
              <receivedMessage>Soco</receivedMessage>
            </script>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ForeverBrick">
                  <brickId>69d0e1d4-f16d-4849-9eb8-6c82670ce0a5</brickId>
                  <commentedOut>true</commentedOut>
                  <loopBricks>
                    <brick type="IfThenLogicBeginBrick">
                      <brickId>f958cd49-132f-4d9f-ac0b-718b99b11949</brickId>
                      <commentedOut>true</commentedOut>
                      <formulaList>
                        <formula category="IF_CONDITION">
                          <additionalChildren/>
                          <leftChild>
                            <additionalChildren/>
                            <type>COLLISION_FORMULA</type>
                            <value>Vegeta</value>
                          </leftChild>
                          <rightChild>
                            <additionalChildren/>
                            <type>FUNCTION</type>
                            <value>TRUE</value>
                          </rightChild>
                          <type>OPERATOR</type>
                          <value>EQUAL</value>
                        </formula>
                      </formulaList>
                      <ifBranchBricks>
                        <brick type="ChangeVariableBrick">
                          <brickId>54245e4a-aab4-41f1-a2a1-146e6e1e1a83</brickId>
                          <commentedOut>true</commentedOut>
                          <formulaList>
                            <formula category="VARIABLE_CHANGE">
                              <additionalChildren/>
                              <rightChild>
                                <additionalChildren/>
                                <type>NUMBER</type>
                                <value>1</value>
                              </rightChild>
                              <type>OPERATOR</type>
                              <value>MINUS</value>
                            </formula>
                          </formulaList>
                          <userVariable reference="../../../../../../../../../../../../scene[4]/objectList/object[4]/scriptList/script[6]/brickList/brick/loopBricks/brick/ifBranchBricks/brick/userVariable"/>
                        </brick>
                        <brick type="WaitBrick">
                          <brickId>575b8ef3-1076-4b58-a013-65be0bab9b36</brickId>
                          <commentedOut>true</commentedOut>
                          <formulaList>
                            <formula category="TIME_TO_WAIT_IN_SECONDS">
                              <additionalChildren/>
                              <type>NUMBER</type>
                              <value>0.2</value>
                            </formula>
                          </formulaList>
                        </brick>
                        <brick type="ChangeVariableBrick">
                          <brickId>60967772-f0c6-4c1d-9f62-0ae9b35b97e9</brickId>
                          <commentedOut>true</commentedOut>
                          <formulaList>
                            <formula category="VARIABLE_CHANGE">
                              <additionalChildren/>
                              <rightChild>
                                <additionalChildren/>
                                <type>NUMBER</type>
                                <value>1</value>
                              </rightChild>
                              <type>OPERATOR</type>
                              <value>MINUS</value>
                            </formula>
                          </formulaList>
                          <userVariable reference="../../../../../../../../../../../../scene[4]/objectList/object[4]/scriptList/script[6]/brickList/brick/loopBricks/brick/ifBranchBricks/brick/userVariable"/>
                        </brick>
                        <brick type="WaitBrick">
                          <brickId>f7e264e1-5100-4927-b901-c91eda9e7e4d</brickId>
                          <commentedOut>true</commentedOut>
                          <formulaList>
                            <formula category="TIME_TO_WAIT_IN_SECONDS">
                              <additionalChildren/>
                              <type>NUMBER</type>
                              <value>0.2</value>
                            </formula>
                          </formulaList>
                        </brick>
                        <brick type="ChangeVariableBrick">
                          <brickId>52ec1d0b-ff50-4aa8-800b-5c946dc25034</brickId>
                          <commentedOut>true</commentedOut>
                          <formulaList>
                            <formula category="VARIABLE_CHANGE">
                              <additionalChildren/>
                              <rightChild>
                                <additionalChildren/>
                                <type>NUMBER</type>
                                <value>1</value>
                              </rightChild>
                              <type>OPERATOR</type>
                              <value>MINUS</value>
                            </formula>
                          </formulaList>
                          <userVariable reference="../../../../../../../../../../../../scene[4]/objectList/object[4]/scriptList/script[6]/brickList/brick/loopBricks/brick/ifBranchBricks/brick/userVariable"/>
                        </brick>
                        <brick type="WaitBrick">
                          <brickId>50e2a51f-8b57-479c-815c-3a432c655330</brickId>
                          <commentedOut>true</commentedOut>
                          <formulaList>
                            <formula category="TIME_TO_WAIT_IN_SECONDS">
                              <additionalChildren/>
                              <type>NUMBER</type>
                              <value>0.2</value>
                            </formula>
                          </formulaList>
                        </brick>
                        <brick type="ChangeVariableBrick">
                          <brickId>9176602e-2666-47a5-b2c6-1a5585d829d5</brickId>
                          <commentedOut>true</commentedOut>
                          <formulaList>
                            <formula category="VARIABLE_CHANGE">
                              <additionalChildren/>
                              <rightChild>
                                <additionalChildren/>
                                <type>NUMBER</type>
                                <value>1</value>
                              </rightChild>
                              <type>OPERATOR</type>
                              <value>MINUS</value>
                            </formula>
                          </formulaList>
                          <userVariable reference="../../../../../../../../../../../../scene[4]/objectList/object[4]/scriptList/script[6]/brickList/brick/loopBricks/brick/ifBranchBricks/brick/userVariable"/>
                        </brick>
                        <brick type="WaitBrick">
                          <brickId>1a3307af-c7b0-4f4c-a408-3b91c8440263</brickId>
                          <commentedOut>true</commentedOut>
                          <formulaList>
                            <formula category="TIME_TO_WAIT_IN_SECONDS">
                              <additionalChildren/>
                              <type>NUMBER</type>
                              <value>0.2</value>
                            </formula>
                          </formulaList>
                        </brick>
                        <brick type="ChangeVariableBrick">
                          <brickId>abf5e26f-a740-46b0-96b2-2d794d9edd0e</brickId>
                          <commentedOut>true</commentedOut>
                          <formulaList>
                            <formula category="VARIABLE_CHANGE">
                              <additionalChildren/>
                              <rightChild>
                                <additionalChildren/>
                                <type>NUMBER</type>
                                <value>1</value>
                              </rightChild>
                              <type>OPERATOR</type>
                              <value>MINUS</value>
                            </formula>
                          </formulaList>
                          <userVariable reference="../../../../../../../../../../../../scene[4]/objectList/object[4]/scriptList/script[6]/brickList/brick/loopBricks/brick/ifBranchBricks/brick/userVariable"/>
                        </brick>
                      </ifBranchBricks>
                    </brick>
                  </loopBricks>
                </brick>
              </brickList>
              <commentedOut>true</commentedOut>
              <scriptId>4c154e8c-ab35-467d-9bf1-fdfa598f7089</scriptId>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetLookBrick">
                  <brickId>fec747e0-5da6-46de-8ed1-5265835a79b2</brickId>
                  <commentedOut>false</commentedOut>
                  <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#10.png" name="Kibast">
                    <isWebRequest>false</isWebRequest>
                    <valid>true</valid>
                  </look>
                </brick>
                <brick type="WaitBrick">
                  <brickId>6189925f-ae39-4fcc-8e1e-f9943c26057e</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.3</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>b267ae86-c866-4d85-bb9b-17ff9b970c19</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../script[3]/brickList/brick/look"/>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>beaec0dd-9eaf-47fe-9f12-7ca11d6b7ff8</scriptId>
              <receivedMessage>Kibast</receivedMessage>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetLookBrick">
                  <brickId>065f67cc-dcc6-4c7e-880b-d122ab9dda4a</brickId>
                  <commentedOut>false</commentedOut>
                  <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#11.png" name="Morte 1">
                    <isWebRequest>false</isWebRequest>
                    <valid>true</valid>
                  </look>
                </brick>
                <brick type="WaitBrick">
                  <brickId>7c110133-64b1-4dcc-b505-effa76099ebb</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.5</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>bedec3ee-1110-4203-b602-ac5d079dcf37</brickId>
                  <commentedOut>false</commentedOut>
                  <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#12.png" name="Morte 2">
                    <isWebRequest>false</isWebRequest>
                    <valid>true</valid>
                  </look>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>b29dd272-e06c-4044-8e7e-38aedc99ebd8</scriptId>
              <receivedMessage>Mortegoku</receivedMessage>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="HideBrick">
                  <brickId>77a1b035-d485-4f8e-b319-080928edaa94</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>98eb9d41-8a25-481a-86e1-143b637ea8d6</scriptId>
              <receivedMessage>Sumir goku</receivedMessage>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetLookBrick">
                  <brickId>e5ae207c-967e-4869-9dbf-86a57b16a344</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../script[7]/brickList/brick/look"/>
                </brick>
                <brick type="WaitBrick">
                  <brickId>b6ec8101-a5c2-4ec4-9d36-de6e40937f18</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.1</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>26833eac-000d-4476-9b08-0be345e22aa6</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../script[3]/brickList/brick/look"/>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>06b02ebb-7bc8-4274-803c-060124ab419a</scriptId>
              <receivedMessage>Gamehameha</receivedMessage>
            </script>
            <script type="WhenConditionScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ChangeXByNBrick">
                  <brickId>b3511dca-2ba8-4a4c-8a2a-d3e5297bc63b</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION_CHANGE">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>10</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>bbc8df27-7445-4664-bee4-06f1a2c30bbc</scriptId>
              <formulaMap>
                <formula category="IF_CONDITION">
                  <additionalChildren/>
                  <leftChild>
                    <additionalChildren/>
                    <type>COLLISION_FORMULA</type>
                    <value>Barreira </value>
                  </leftChild>
                  <rightChild>
                    <additionalChildren/>
                    <type>FUNCTION</type>
                    <value>TRUE</value>
                  </rightChild>
                  <type>OPERATOR</type>
                  <value>EQUAL</value>
                </formula>
              </formulaMap>
            </script>
            <script type="WhenConditionScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ChangeXByNBrick">
                  <brickId>32e26769-16c1-49e1-b9ba-db63d7d27b51</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION_CHANGE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>10</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>edd43f72-589f-4fcd-836e-6e9b04d88646</scriptId>
              <formulaMap>
                <formula category="IF_CONDITION">
                  <additionalChildren/>
                  <leftChild>
                    <additionalChildren/>
                    <type>COLLISION_FORMULA</type>
                    <value>Barreira  (1)</value>
                  </leftChild>
                  <rightChild>
                    <additionalChildren/>
                    <type>FUNCTION</type>
                    <value>TRUE</value>
                  </rightChild>
                  <type>OPERATOR</type>
                  <value>EQUAL</value>
                </formula>
              </formulaMap>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Vegeta">
          <lookList/>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>3518bd38-1678-4a1e-a05d-d2f240062e75</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>744</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>259</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>a9d3c818-67af-474d-ac10-0572d5adb7bb</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>500</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>f0372eae-0ec8-4e88-8a4e-cec38f1bd830</scriptId>
            </script>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ForeverBrick">
                  <brickId>dac4ee18-c83b-4937-8dfb-8a3f7929ed40</brickId>
                  <commentedOut>false</commentedOut>
                  <loopBricks>
                    <brick type="PointToBrick">
                      <brickId>fe61dafe-45ad-4670-bccb-0d6c474048e6</brickId>
                      <commentedOut>false</commentedOut>
                      <pointedObject reference="../../../../../../../../../../scene[4]/objectList/object[4]"/>
                    </brick>
                    <brick type="SetRotationStyleBrick">
                      <brickId>62669823-a45f-4a1d-9ae0-ddc8a20f4e2c</brickId>
                      <commentedOut>false</commentedOut>
                      <selection>0</selection>
                    </brick>
                  </loopBricks>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>3db747ac-5ec1-49ea-9ffd-a5a66e2cb52f</scriptId>
            </script>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ForeverBrick">
                  <brickId>64e039a2-1980-4c70-8f87-fe43c6c6593e</brickId>
                  <commentedOut>false</commentedOut>
                  <loopBricks>
                    <brick type="WaitBrick">
                      <brickId>cbc6effa-fe4d-473e-9f6c-ddffe4f4a1f8</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="TIME_TO_WAIT_IN_SECONDS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>2</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="RepeatUntilBrick">
                      <brickId>d48dc80d-98ab-4d7f-8b3a-9fbb0f5f9fd6</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="REPEAT_UNTIL_CONDITION">
                          <additionalChildren/>
                          <leftChild>
                            <additionalChildren/>
                            <type>COLLISION_FORMULA</type>
                            <value>Goku</value>
                          </leftChild>
                          <rightChild>
                            <additionalChildren/>
                            <type>FUNCTION</type>
                            <value>TRUE</value>
                          </rightChild>
                          <type>OPERATOR</type>
                          <value>EQUAL</value>
                        </formula>
                      </formulaList>
                      <loopBricks>
                        <brick type="MoveNStepsBrick">
                          <brickId>1418f1a5-88b3-44a6-94a6-82b1d3789e1f</brickId>
                          <commentedOut>false</commentedOut>
                          <formulaList>
                            <formula category="STEPS">
                              <additionalChildren/>
                              <type>NUMBER</type>
                              <value>7</value>
                            </formula>
                          </formulaList>
                        </brick>
                        <brick type="SetLookBrick">
                          <brickId>65ec5fb0-70c6-4bf6-ac30-dc9cacebe916</brickId>
                          <commentedOut>false</commentedOut>
                          <look fileName="vegeta___ultimate_lsw_sheet_by_qsab101_dbzqwt5_#2.png" name="Voando">
                            <isWebRequest>false</isWebRequest>
                            <valid>true</valid>
                          </look>
                        </brick>
                      </loopBricks>
                    </brick>
                  </loopBricks>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>a84d5d14-e483-4783-8970-267fe1fd804d</scriptId>
            </script>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ForeverBrick">
                  <brickId>ecab4f3f-8bfc-4b6c-abcb-174042a5f8d5</brickId>
                  <commentedOut>false</commentedOut>
                  <loopBricks>
                    <brick type="IfThenLogicBeginBrick">
                      <brickId>c06fc84a-bb60-4f37-911e-cdbafd34ce7a</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="IF_CONDITION">
                          <additionalChildren/>
                          <leftChild>
                            <additionalChildren/>
                            <type>COLLISION_FORMULA</type>
                            <value>Goku</value>
                          </leftChild>
                          <rightChild>
                            <additionalChildren/>
                            <type>FUNCTION</type>
                            <value>TRUE</value>
                          </rightChild>
                          <type>OPERATOR</type>
                          <value>EQUAL</value>
                        </formula>
                      </formulaList>
                      <ifBranchBricks>
                        <brick type="SetLookBrick">
                          <brickId>d6cc0050-2385-41ca-99de-0ba7876e5fd6</brickId>
                          <commentedOut>false</commentedOut>
                          <look fileName="vegeta___ultimate_lsw_sheet_by_qsab101_dbzqwt5.png" name="Soco 1">
                            <isWebRequest>false</isWebRequest>
                            <valid>true</valid>
                          </look>
                        </brick>
                        <brick type="ChangeVariableBrick">
                          <brickId>e6b7c62d-3aff-42b2-b34f-edf9ae3209a2</brickId>
                          <commentedOut>false</commentedOut>
                          <formulaList>
                            <formula category="VARIABLE_CHANGE">
                              <additionalChildren/>
                              <rightChild>
                                <additionalChildren/>
                                <type>NUMBER</type>
                                <value>1</value>
                              </rightChild>
                              <type>OPERATOR</type>
                              <value>MINUS</value>
                            </formula>
                          </formulaList>
                          <userVariable reference="../../../../../../../../../../../../scene[4]/objectList/object[4]/scriptList/script/brickList/brick[4]/loopBricks/brick/pointedObject/scriptList/script[4]/brickList/brick/loopBricks/brick/ifBranchBricks/brick[2]/userVariable"/>
                        </brick>
                        <brick type="WaitBrick">
                          <brickId>d3dd8530-7740-45b9-9532-a6276c6d13ef</brickId>
                          <commentedOut>false</commentedOut>
                          <formulaList>
                            <formula category="TIME_TO_WAIT_IN_SECONDS">
                              <additionalChildren/>
                              <type>NUMBER</type>
                              <value>0.2</value>
                            </formula>
                          </formulaList>
                        </brick>
                        <brick type="SetLookBrick">
                          <brickId>b0b0bab0-4c61-4448-bc0d-830a5d7c6926</brickId>
                          <commentedOut>false</commentedOut>
                          <look fileName="vegeta___ultimate_lsw_sheet_by_qsab101_dbzqwt5_#1.png" name="Soco 2">
                            <isWebRequest>false</isWebRequest>
                            <valid>true</valid>
                          </look>
                        </brick>
                        <brick type="ChangeVariableBrick">
                          <brickId>8f302150-4915-4422-b1db-75ca72e639e2</brickId>
                          <commentedOut>false</commentedOut>
                          <formulaList>
                            <formula category="VARIABLE_CHANGE">
                              <additionalChildren/>
                              <rightChild>
                                <additionalChildren/>
                                <type>NUMBER</type>
                                <value>1</value>
                              </rightChild>
                              <type>OPERATOR</type>
                              <value>MINUS</value>
                            </formula>
                          </formulaList>
                          <userVariable reference="../../../../../../../../../../../../scene[4]/objectList/object[4]/scriptList/script/brickList/brick[4]/loopBricks/brick/pointedObject/scriptList/script[4]/brickList/brick/loopBricks/brick/ifBranchBricks/brick[2]/userVariable"/>
                        </brick>
                        <brick type="WaitBrick">
                          <brickId>078651de-9fca-49a1-8f0c-00ae1d29dbdb</brickId>
                          <commentedOut>false</commentedOut>
                          <formulaList>
                            <formula category="TIME_TO_WAIT_IN_SECONDS">
                              <additionalChildren/>
                              <type>NUMBER</type>
                              <value>0.2</value>
                            </formula>
                          </formulaList>
                        </brick>
                        <brick type="SetLookBrick">
                          <brickId>5fa9828d-ef37-454e-bf86-d2b88aead03e</brickId>
                          <commentedOut>false</commentedOut>
                          <look fileName="vegeta___ultimate_lsw_sheet_by_qsab101_dbzqwt5_#3.png" name="Soco 3">
                            <isWebRequest>false</isWebRequest>
                            <valid>true</valid>
                          </look>
                        </brick>
                        <brick type="ChangeVariableBrick">
                          <brickId>c215891c-85e8-4edf-80bd-49eb90c3e95e</brickId>
                          <commentedOut>false</commentedOut>
                          <formulaList>
                            <formula category="VARIABLE_CHANGE">
                              <additionalChildren/>
                              <rightChild>
                                <additionalChildren/>
                                <type>NUMBER</type>
                                <value>1</value>
                              </rightChild>
                              <type>OPERATOR</type>
                              <value>MINUS</value>
                            </formula>
                          </formulaList>
                          <userVariable reference="../../../../../../../../../../../../scene[4]/objectList/object[4]/scriptList/script/brickList/brick[4]/loopBricks/brick/pointedObject/scriptList/script[4]/brickList/brick/loopBricks/brick/ifBranchBricks/brick[2]/userVariable"/>
                        </brick>
                        <brick type="WaitBrick">
                          <brickId>b19aacbb-4492-4542-b343-1765fff1799e</brickId>
                          <commentedOut>false</commentedOut>
                          <formulaList>
                            <formula category="TIME_TO_WAIT_IN_SECONDS">
                              <additionalChildren/>
                              <type>NUMBER</type>
                              <value>0.2</value>
                            </formula>
                          </formulaList>
                        </brick>
                        <brick type="SetLookBrick">
                          <brickId>8853e537-f969-4446-86fe-87e2a81cb129</brickId>
                          <commentedOut>false</commentedOut>
                          <look fileName="vegeta___ultimate_lsw_sheet_by_qsab101_dbzqwt5_#4.png" name="Soco 4">
                            <isWebRequest>false</isWebRequest>
                            <valid>true</valid>
                          </look>
                        </brick>
                        <brick type="ChangeVariableBrick">
                          <brickId>efe8d7dd-7ffd-495c-b442-83244487dcb8</brickId>
                          <commentedOut>false</commentedOut>
                          <formulaList>
                            <formula category="VARIABLE_CHANGE">
                              <additionalChildren/>
                              <rightChild>
                                <additionalChildren/>
                                <type>NUMBER</type>
                                <value>1</value>
                              </rightChild>
                              <type>OPERATOR</type>
                              <value>MINUS</value>
                            </formula>
                          </formulaList>
                          <userVariable reference="../../../../../../../../../../../../scene[4]/objectList/object[4]/scriptList/script/brickList/brick[4]/loopBricks/brick/pointedObject/scriptList/script[4]/brickList/brick/loopBricks/brick/ifBranchBricks/brick[2]/userVariable"/>
                        </brick>
                        <brick type="WaitBrick">
                          <brickId>fa574511-409a-4f97-8789-82d15e563728</brickId>
                          <commentedOut>false</commentedOut>
                          <formulaList>
                            <formula category="TIME_TO_WAIT_IN_SECONDS">
                              <additionalChildren/>
                              <type>NUMBER</type>
                              <value>0.2</value>
                            </formula>
                          </formulaList>
                        </brick>
                        <brick type="SetLookBrick">
                          <brickId>128d58d2-7d64-4e04-8cd7-1bb0c2e30d56</brickId>
                          <commentedOut>false</commentedOut>
                          <look fileName="vegeta___ultimate_lsw_sheet_by_qsab101_dbzqwt5_#5.png" name="Soco 5">
                            <isWebRequest>false</isWebRequest>
                            <valid>true</valid>
                          </look>
                        </brick>
                        <brick type="ChangeVariableBrick">
                          <brickId>ab44af5d-6d25-4ecb-b6bc-10fc5a51e1d6</brickId>
                          <commentedOut>false</commentedOut>
                          <formulaList>
                            <formula category="VARIABLE_CHANGE">
                              <additionalChildren/>
                              <rightChild>
                                <additionalChildren/>
                                <type>NUMBER</type>
                                <value>3</value>
                              </rightChild>
                              <type>OPERATOR</type>
                              <value>MINUS</value>
                            </formula>
                          </formulaList>
                          <userVariable reference="../../../../../../../../../../../../scene[4]/objectList/object[4]/scriptList/script/brickList/brick[4]/loopBricks/brick/pointedObject/scriptList/script[4]/brickList/brick/loopBricks/brick/ifBranchBricks/brick[2]/userVariable"/>
                        </brick>
                      </ifBranchBricks>
                    </brick>
                  </loopBricks>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>a80b1bcc-1bc4-4f76-9d77-58e07e3886ca</scriptId>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="HideBrick">
                  <brickId>d720c31b-4087-493f-9819-e514bf951141</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>265b6ca4-0795-4c38-bd11-36be70b75934</scriptId>
              <receivedMessage>Sumirvegeta</receivedMessage>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetLookBrick">
                  <brickId>6f34ba20-1465-4d9a-bce5-8c3c1a38f37a</brickId>
                  <commentedOut>false</commentedOut>
                  <look fileName="vegeta___ultimate_lsw_sheet_by_qsab101_dbzqwt5_#6.png" name="Morte 1">
                    <isWebRequest>false</isWebRequest>
                    <valid>true</valid>
                  </look>
                </brick>
                <brick type="WaitBrick">
                  <brickId>2dc0e4b5-02d2-4d3f-b4f3-9985e89a3251</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.3</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>63f96262-c28f-48a4-991f-e41ab979a767</brickId>
                  <commentedOut>false</commentedOut>
                  <look fileName="vegeta___ultimate_lsw_sheet_by_qsab101_dbzqwt5_#7.png" name="Morte 2">
                    <isWebRequest>false</isWebRequest>
                    <valid>true</valid>
                  </look>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>40f44ae4-8ba0-4a22-9ad8-d020a987b9e3</scriptId>
              <receivedMessage>Morte vegeta</receivedMessage>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Goku_Black">
          <lookList/>
          <soundList/>
          <scriptList/>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="&#xa;Soco">
          <lookList/>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>c86e780b-e967-42d0-a834-2e77b983792c</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>1088</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>460</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>b6927477-6c1c-4022-ab92-d84b2b38292f</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>600</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>e1ce83cd-6291-40d6-9c5a-22796baf70f7</scriptId>
            </script>
            <script type="WhenScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetSizeToBrick">
                  <brickId>df1e4f34-1bb0-4dca-bf41-f67dbda28c4a</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>500</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="WaitBrick">
                  <brickId>209ed358-e931-484c-a04e-b2dd1ad44f57</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.2</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>0956a20a-687a-414e-93c9-578e9cc8fb66</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>600</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="BroadcastBrick">
                  <brickId>53afa419-fb50-4710-b53e-428537f5b977</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Soco</broadcastMessage>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>2abdd130-e753-4a0a-b2a0-d1680f232d42</scriptId>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="HideBrick">
                  <brickId>2e487c92-7c95-4759-a48b-82d7f33ac9ec</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>de26cd31-d16f-4240-8297-2025a5daeaf3</scriptId>
              <receivedMessage>Mortegoku</receivedMessage>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Vida goku">
          <lookList/>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>43d86356-75e8-4076-b978-69350a4a3a04</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>769</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>451</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>1a1b2cc5-5603-493c-aa4c-2ef91dd2d49c</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>400</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetVariableBrick">
                  <brickId>44967c61-8858-43f9-b5bc-810f8beec75a</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="VARIABLE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>100</value>
                    </formula>
                  </formulaList>
                  <userVariable reference="../../../../../../../../scene[4]/objectList/object[4]/scriptList/script/brickList/brick[4]/loopBricks/brick/pointedObject/scriptList/script[4]/brickList/brick/loopBricks/brick/ifBranchBricks/brick[2]/userVariable"/>
                </brick>
                <brick type="ShowTextBrick">
                  <brickId>be9da17d-c861-494d-99ae-1e28ae3e6df5</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>400</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>571</value>
                    </formula>
                  </formulaList>
                  <userVariable reference="../../../../../../../../scene[4]/objectList/object[4]/scriptList/script/brickList/brick[4]/loopBricks/brick/pointedObject/scriptList/script[4]/brickList/brick/loopBricks/brick/ifBranchBricks/brick[2]/userVariable"/>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>4aa65393-838f-4dde-8fec-3e6d8e109367</scriptId>
            </script>
            <script type="WhenConditionScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="BroadcastBrick">
                  <brickId>e466cbfe-6614-445d-8534-1fae92a67e3c</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Sumirvegeta</broadcastMessage>
                </brick>
                <brick type="BroadcastBrick">
                  <brickId>b7f9f236-7006-4ae4-8936-429f0d7efe06</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Mortegoku</broadcastMessage>
                </brick>
                <brick type="WaitBrick">
                  <brickId>37068a84-b663-458c-ba54-3f1950576640</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>3</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SceneStartBrick">
                  <brickId>54d88f31-8afb-416d-9636-1c0a4ad72d4c</brickId>
                  <commentedOut>false</commentedOut>
                  <sceneToStart>Game over</sceneToStart>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>621f5f81-f4b3-4d03-ae0a-aee5a4f0ebbf</scriptId>
              <formulaMap>
                <formula category="IF_CONDITION">
                  <additionalChildren/>
                  <leftChild>
                    <additionalChildren/>
                    <type>USER_VARIABLE</type>
                    <value>Vida_Goku</value>
                  </leftChild>
                  <rightChild>
                    <additionalChildren/>
                    <rightChild>
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>2</value>
                    </rightChild>
                    <type>OPERATOR</type>
                    <value>MINUS</value>
                  </rightChild>
                  <type>OPERATOR</type>
                  <value>EQUAL</value>
                </formula>
              </formulaMap>
            </script>
            <script type="WhenConditionScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="BroadcastBrick">
                  <brickId>e72ffb70-3680-42d5-99fc-49485a99342c</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Sumirvegeta</broadcastMessage>
                </brick>
                <brick type="BroadcastBrick">
                  <brickId>8fcfd4fd-4dca-48ee-bf9c-08a3a84ef7bf</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Mortegoku</broadcastMessage>
                </brick>
                <brick type="WaitBrick">
                  <brickId>d9060ba4-604c-424b-aaf8-6d284cbd1c98</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>3</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SceneStartBrick">
                  <brickId>4bffec1d-a773-4111-bed5-311c06b6f124</brickId>
                  <commentedOut>false</commentedOut>
                  <sceneToStart>Game over</sceneToStart>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>a4cf0ea9-10e1-4d7b-bb58-5ee1f2018f60</scriptId>
              <formulaMap>
                <formula category="IF_CONDITION">
                  <additionalChildren/>
                  <leftChild>
                    <additionalChildren/>
                    <type>USER_VARIABLE</type>
                    <value>Vida_Goku</value>
                  </leftChild>
                  <rightChild>
                    <additionalChildren/>
                    <rightChild>
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>1</value>
                    </rightChild>
                    <type>OPERATOR</type>
                    <value>MINUS</value>
                  </rightChild>
                  <type>OPERATOR</type>
                  <value>EQUAL</value>
                </formula>
              </formulaMap>
            </script>
            <script type="WhenConditionScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="BroadcastBrick">
                  <brickId>1ef20dbc-c8c9-4918-874f-173220ea8922</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Sumirvegeta</broadcastMessage>
                </brick>
                <brick type="BroadcastBrick">
                  <brickId>3103fe14-d0e9-4e5e-840e-eb74796cda3b</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Mortegoku</broadcastMessage>
                </brick>
                <brick type="WaitBrick">
                  <brickId>88e31756-f0e1-4d2e-8956-02b2690f200d</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>3</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SceneStartBrick">
                  <brickId>9eff94e5-95f6-4fc8-a708-61dc6c8dc75d</brickId>
                  <commentedOut>false</commentedOut>
                  <sceneToStart>You win</sceneToStart>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>22519af3-a822-4ded-b52b-4697c5758fc2</scriptId>
              <formulaMap>
                <formula category="IF_CONDITION">
                  <additionalChildren/>
                  <leftChild>
                    <additionalChildren/>
                    <type>USER_VARIABLE</type>
                    <value>Vida_Goku</value>
                  </leftChild>
                  <rightChild>
                    <additionalChildren/>
                    <rightChild>
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>3</value>
                    </rightChild>
                    <type>OPERATOR</type>
                    <value>MINUS</value>
                  </rightChild>
                  <type>OPERATOR</type>
                  <value>EQUAL</value>
                </formula>
              </formulaMap>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Vida bot">
          <lookList/>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>d47c522c-1c82-49bb-895b-3ae0da53e9d6</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>770</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>440</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>7957dace-2345-469d-86b0-8aa0c9ca7bc7</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>400</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetVariableBrick">
                  <brickId>225b645f-9312-432e-aad1-dacc97831a88</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="VARIABLE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>100</value>
                    </formula>
                  </formulaList>
                  <userVariable reference="../../../../../../../../scene[4]/objectList/object[4]/scriptList/script[6]/brickList/brick/loopBricks/brick/ifBranchBricks/brick/userVariable"/>
                </brick>
                <brick type="ShowTextBrick">
                  <brickId>8fc082ed-f946-4a56-8cbd-ffb2f37ec720</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>400</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>571</value>
                    </formula>
                  </formulaList>
                  <userVariable reference="../../../../../../../../scene[4]/objectList/object[4]/scriptList/script[6]/brickList/brick/loopBricks/brick/ifBranchBricks/brick/userVariable"/>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>68a6546c-a031-459f-bafe-78cbb6bd7154</scriptId>
            </script>
            <script type="WhenConditionScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="BroadcastBrick">
                  <brickId>3d6d3026-ed27-4623-a02d-351ae4fd7c40</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Morte vegeta</broadcastMessage>
                </brick>
                <brick type="BroadcastBrick">
                  <brickId>aafd351c-18be-4c3c-95c1-51a7c365732f</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Sumir goku</broadcastMessage>
                </brick>
                <brick type="WaitBrick">
                  <brickId>60de7910-93c1-43df-8aad-f55222dffeed</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>3</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SceneStartBrick">
                  <brickId>f2cea8e4-744b-4562-a2b1-2a939ab2cd52</brickId>
                  <commentedOut>false</commentedOut>
                  <sceneToStart>You win</sceneToStart>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>a6cd4c9d-06bb-4ce6-b9b0-d52a86386c69</scriptId>
              <formulaMap>
                <formula category="IF_CONDITION">
                  <additionalChildren/>
                  <leftChild>
                    <additionalChildren/>
                    <type>USER_VARIABLE</type>
                    <value>Vida_bot</value>
                  </leftChild>
                  <rightChild>
                    <additionalChildren/>
                    <rightChild>
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>2</value>
                    </rightChild>
                    <type>OPERATOR</type>
                    <value>MINUS</value>
                  </rightChild>
                  <type>OPERATOR</type>
                  <value>EQUAL</value>
                </formula>
              </formulaMap>
            </script>
            <script type="WhenConditionScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="BroadcastBrick">
                  <brickId>ee09666a-90e7-497b-88d9-8b9d5aa174e3</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Morte vegeta</broadcastMessage>
                </brick>
                <brick type="BroadcastBrick">
                  <brickId>fbca86d6-0ec8-4259-b921-1383447e3e20</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Sumir goku</broadcastMessage>
                </brick>
                <brick type="WaitBrick">
                  <brickId>ff514329-7654-4139-bef6-c9a47a1820bd</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>3</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SceneStartBrick">
                  <brickId>acec0174-a0c0-4480-81fe-35c40d7cc281</brickId>
                  <commentedOut>false</commentedOut>
                  <sceneToStart>You win</sceneToStart>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>9d5bf7a9-7668-4b09-8b92-874ddd15db0b</scriptId>
              <formulaMap>
                <formula category="IF_CONDITION">
                  <additionalChildren/>
                  <leftChild>
                    <additionalChildren/>
                    <type>USER_VARIABLE</type>
                    <value>Vida_bot</value>
                  </leftChild>
                  <rightChild>
                    <additionalChildren/>
                    <rightChild>
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>1</value>
                    </rightChild>
                    <type>OPERATOR</type>
                    <value>MINUS</value>
                  </rightChild>
                  <type>OPERATOR</type>
                  <value>EQUAL</value>
                </formula>
              </formulaMap>
            </script>
            <script type="WhenConditionScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="BroadcastBrick">
                  <brickId>07dc533a-1978-4da2-a19e-3e0fdc17c6b2</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Morte vegeta</broadcastMessage>
                </brick>
                <brick type="BroadcastBrick">
                  <brickId>30ea2c85-1d36-437d-830f-ec2b5eb1b237</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Sumir goku</broadcastMessage>
                </brick>
                <brick type="WaitBrick">
                  <brickId>36690d59-0b84-499f-9b27-28b193f4cb2d</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>3</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SceneStartBrick">
                  <brickId>eb30fa24-b5f9-4add-8aaa-fc6dee660fe9</brickId>
                  <commentedOut>false</commentedOut>
                  <sceneToStart>You win</sceneToStart>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>bb8b4a2d-7933-448f-bf50-a9b904110ed5</scriptId>
              <formulaMap>
                <formula category="IF_CONDITION">
                  <additionalChildren/>
                  <leftChild>
                    <additionalChildren/>
                    <type>USER_VARIABLE</type>
                    <value>Vida_bot</value>
                  </leftChild>
                  <rightChild>
                    <additionalChildren/>
                    <rightChild>
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>3</value>
                    </rightChild>
                    <type>OPERATOR</type>
                    <value>MINUS</value>
                  </rightChild>
                  <type>OPERATOR</type>
                  <value>EQUAL</value>
                </formula>
              </formulaMap>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Imagem da vida goku">
          <lookList/>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>74ddf5fb-96d6-41a6-8785-57a68d351c4e</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>1071</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>449</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>d671d1c3-d864-406c-8dbc-827c5a6b9717</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>250</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>0907651e-1e30-4f83-bef1-220f3a202fc1</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Botão Ki">
          <lookList/>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>72b1e48c-f28c-4829-aa26-e1b8daf0a21a</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>900</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>464</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>7c156be5-dbf0-4dc6-a3d5-c06828eff821</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>600</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>a54fe66e-64da-4c9c-989d-aa7fb9c9d10f</scriptId>
            </script>
            <script type="WhenScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="BroadcastBrick">
                  <brickId>08dbc761-22f0-4e01-8396-95909ae0a4c5</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Kibast</broadcastMessage>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>4c88d230-2daf-4d47-8191-76bd3211c83d</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>500</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="WaitBrick">
                  <brickId>9ca6107e-8ae7-4daf-bd2a-45921f834966</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.2</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>e06426b4-998d-49dd-81d7-8434a3173f26</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>600</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="HideBrick">
                  <brickId>f96b04ab-299d-481f-a7a7-d16dd97071cc</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
                <brick type="WaitBrick">
                  <brickId>15363890-d6e8-44df-8ff9-e733654ce7d0</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>3</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="ShowBrick">
                  <brickId>b5865a88-5d60-4c37-9192-394305e90e59</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>8712465b-64af-40ba-9ecb-9ddd0e903d81</scriptId>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="HideBrick">
                  <brickId>1ebe8ed1-da5d-49ba-9687-d5c6c5476ddf</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>670f32cb-da4d-4217-8071-219e60e6b547</scriptId>
              <receivedMessage>Mortegoku</receivedMessage>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Hitsoco">
          <lookList/>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetTransparencyBrick">
                  <brickId>d93b4c5c-b563-4794-a7ed-480b08a4e939</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TRANSPARENCY">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>80</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="HideBrick">
                  <brickId>ddf2e1a8-82f7-48df-9a3f-da5f6c38e7f1</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>d76a5cdc-7c59-4eba-b8b0-98bf48037cd3</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>500</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="ForeverBrick">
                  <brickId>ee28da4e-d3d0-4387-91cb-5481b652f4a9</brickId>
                  <commentedOut>false</commentedOut>
                  <loopBricks>
                    <brick type="GoToBrick">
                      <brickId>ae50db98-7b40-4ec7-8d5e-064a12d56566</brickId>
                      <commentedOut>false</commentedOut>
                      <destinationSprite reference="../../../../../../../../../../scene[4]/objectList/object[4]"/>
                      <spinnerSelection>82</spinnerSelection>
                    </brick>
                  </loopBricks>
                </brick>
                <brick type="SetXBrick">
                  <brickId>ae6657e2-bb85-4852-a41d-b32870778f99</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>50</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>a0c4eeac-db42-42a9-96b4-9eeb44a54fa7</scriptId>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ShowBrick">
                  <brickId>91e647ff-77f5-4d30-86d6-4a7c3afa0e23</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
                <brick type="WaitBrick">
                  <brickId>b51fccc4-a129-4911-adeb-20fbeee22aad</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.2</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="HideBrick">
                  <brickId>df2ba9e5-80d0-4290-a0f8-23433a87fc46</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>fb1a22e1-5342-4437-8b66-82feafeda824</scriptId>
              <receivedMessage>Soco</receivedMessage>
            </script>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ForeverBrick">
                  <brickId>f1a6c01c-15e4-416b-b469-816a6c2f6bff</brickId>
                  <commentedOut>false</commentedOut>
                  <loopBricks>
                    <brick type="IfThenLogicBeginBrick">
                      <brickId>074e3499-6843-4338-a76d-bbaa506baafd</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="IF_CONDITION">
                          <additionalChildren/>
                          <leftChild>
                            <additionalChildren/>
                            <type>COLLISION_FORMULA</type>
                            <value>Vegeta</value>
                          </leftChild>
                          <rightChild>
                            <additionalChildren/>
                            <type>FUNCTION</type>
                            <value>TRUE</value>
                          </rightChild>
                          <type>OPERATOR</type>
                          <value>EQUAL</value>
                        </formula>
                      </formulaList>
                      <ifBranchBricks>
                        <brick type="SetLookBrick">
                          <brickId>da0e0c8c-8773-438a-8130-b3cbd2ca6e2e</brickId>
                          <commentedOut>false</commentedOut>
                          <look fileName="Meu ator ou objeto.png" name="Hitsoco">
                            <isWebRequest>false</isWebRequest>
                            <valid>true</valid>
                          </look>
                        </brick>
                        <brick type="ChangeVariableBrick">
                          <brickId>b170a526-ef2d-4a49-bcc0-19e4d4dff4ce</brickId>
                          <commentedOut>false</commentedOut>
                          <formulaList>
                            <formula category="VARIABLE_CHANGE">
                              <additionalChildren/>
                              <rightChild>
                                <additionalChildren/>
                                <type>NUMBER</type>
                                <value>1</value>
                              </rightChild>
                              <type>OPERATOR</type>
                              <value>MINUS</value>
                            </formula>
                          </formulaList>
                          <userVariable reference="../../../../../../../../../../../../scene[4]/objectList/object[4]/scriptList/script[6]/brickList/brick/loopBricks/brick/ifBranchBricks/brick/userVariable"/>
                        </brick>
                        <brick type="WaitBrick">
                          <brickId>9d602c07-b7f0-48c0-bbec-8ecfc5defca0</brickId>
                          <commentedOut>false</commentedOut>
                          <formulaList>
                            <formula category="TIME_TO_WAIT_IN_SECONDS">
                              <additionalChildren/>
                              <type>NUMBER</type>
                              <value>0.2</value>
                            </formula>
                          </formulaList>
                        </brick>
                        <brick type="SetLookBrick">
                          <brickId>4f1598db-3f9c-4bb4-b279-3d6d4233d78c</brickId>
                          <commentedOut>false</commentedOut>
                          <look reference="../../brick/look"/>
                        </brick>
                        <brick type="ChangeVariableBrick">
                          <brickId>bd4a5367-5352-4bf3-91a3-123029034d3a</brickId>
                          <commentedOut>false</commentedOut>
                          <formulaList>
                            <formula category="VARIABLE_CHANGE">
                              <additionalChildren/>
                              <rightChild>
                                <additionalChildren/>
                                <type>NUMBER</type>
                                <value>1</value>
                              </rightChild>
                              <type>OPERATOR</type>
                              <value>MINUS</value>
                            </formula>
                          </formulaList>
                          <userVariable reference="../../../../../../../../../../../../scene[4]/objectList/object[4]/scriptList/script[6]/brickList/brick/loopBricks/brick/ifBranchBricks/brick/userVariable"/>
                        </brick>
                        <brick type="WaitBrick">
                          <brickId>72dbcd6a-0662-4ad5-84dd-e15f33b757d5</brickId>
                          <commentedOut>false</commentedOut>
                          <formulaList>
                            <formula category="TIME_TO_WAIT_IN_SECONDS">
                              <additionalChildren/>
                              <type>NUMBER</type>
                              <value>0.2</value>
                            </formula>
                          </formulaList>
                        </brick>
                        <brick type="SetLookBrick">
                          <brickId>e7290df7-4ee3-41a7-a20f-0d59e1cd79d4</brickId>
                          <commentedOut>false</commentedOut>
                          <look reference="../../brick/look"/>
                        </brick>
                        <brick type="ChangeVariableBrick">
                          <brickId>5e9fe2ee-71a6-42ce-a09a-bf91e25feca1</brickId>
                          <commentedOut>false</commentedOut>
                          <formulaList>
                            <formula category="VARIABLE_CHANGE">
                              <additionalChildren/>
                              <rightChild>
                                <additionalChildren/>
                                <type>NUMBER</type>
                                <value>1</value>
                              </rightChild>
                              <type>OPERATOR</type>
                              <value>MINUS</value>
                            </formula>
                          </formulaList>
                          <userVariable reference="../../../../../../../../../../../../scene[4]/objectList/object[4]/scriptList/script[6]/brickList/brick/loopBricks/brick/ifBranchBricks/brick/userVariable"/>
                        </brick>
                        <brick type="WaitBrick">
                          <brickId>613aa911-d6af-4a5b-be11-c48cdb3bc8a9</brickId>
                          <commentedOut>false</commentedOut>
                          <formulaList>
                            <formula category="TIME_TO_WAIT_IN_SECONDS">
                              <additionalChildren/>
                              <type>NUMBER</type>
                              <value>0.2</value>
                            </formula>
                          </formulaList>
                        </brick>
                        <brick type="SetLookBrick">
                          <brickId>0c6c3750-8837-480a-b3b0-0980af5899a0</brickId>
                          <commentedOut>false</commentedOut>
                          <look reference="../../brick/look"/>
                        </brick>
                      </ifBranchBricks>
                    </brick>
                  </loopBricks>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>e5559676-2f50-4d56-88ac-f6b58e3a044b</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Kiblast">
          <lookList/>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>35701af7-477a-471f-9350-056fb7f990a4</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>134</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>640</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>6f7ed3e0-8989-43d4-baf0-faf73ec031f1</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>300</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="HideBrick">
                  <brickId>697aa0b1-2c1d-4206-bf07-824beab1ee2d</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>67e792c4-900c-4e48-aa2a-6b9bea4e696e</scriptId>
            </script>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ForeverBrick">
                  <brickId>bf967b09-f250-49be-8e87-77b623f9812d</brickId>
                  <commentedOut>false</commentedOut>
                  <loopBricks>
                    <brick type="IfThenLogicBeginBrick">
                      <brickId>78999d7e-372c-481d-ac73-7845eaaaa839</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="IF_CONDITION">
                          <additionalChildren/>
                          <leftChild>
                            <additionalChildren/>
                            <type>COLLISION_FORMULA</type>
                            <value>Vegeta</value>
                          </leftChild>
                          <rightChild>
                            <additionalChildren/>
                            <type>FUNCTION</type>
                            <value>TRUE</value>
                          </rightChild>
                          <type>OPERATOR</type>
                          <value>EQUAL</value>
                        </formula>
                      </formulaList>
                      <ifBranchBricks>
                        <brick type="ChangeVariableBrick">
                          <brickId>95b2775f-084b-474c-ab8a-b9c2a2fb3baa</brickId>
                          <commentedOut>false</commentedOut>
                          <formulaList>
                            <formula category="VARIABLE_CHANGE">
                              <additionalChildren/>
                              <rightChild>
                                <additionalChildren/>
                                <type>NUMBER</type>
                                <value>5</value>
                              </rightChild>
                              <type>OPERATOR</type>
                              <value>MINUS</value>
                            </formula>
                          </formulaList>
                          <userVariable reference="../../../../../../../../../../../../scene[4]/objectList/object[4]/scriptList/script[6]/brickList/brick/loopBricks/brick/ifBranchBricks/brick/userVariable"/>
                        </brick>
                        <brick type="ShowBrick">
                          <brickId>139bbd08-951c-44ae-9108-5bfe26b7cc37</brickId>
                          <commentedOut>true</commentedOut>
                        </brick>
                        <brick type="HideBrick">
                          <brickId>fe29c300-272a-4d74-b464-e3bdab91464b</brickId>
                          <commentedOut>false</commentedOut>
                        </brick>
                      </ifBranchBricks>
                    </brick>
                  </loopBricks>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>68c80b35-45d5-47b3-a3e8-3abc407e302c</scriptId>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetLookBrick">
                  <brickId>63921ca1-8757-4fa5-8de7-004a0a41c6dc</brickId>
                  <commentedOut>false</commentedOut>
                  <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#6.png" name="Kiblast">
                    <isWebRequest>false</isWebRequest>
                    <valid>true</valid>
                  </look>
                </brick>
                <brick type="WaitBrick">
                  <brickId>24800030-153c-43a5-8a7e-766164fd8c16</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.1</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>81b0df50-716e-4cf7-a890-559a395c0956</brickId>
                  <commentedOut>false</commentedOut>
                  <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#7.png" name="Kiblast (1)">
                    <isWebRequest>false</isWebRequest>
                    <valid>true</valid>
                  </look>
                </brick>
                <brick type="WaitBrick">
                  <brickId>1b3755fa-7ab1-4e5c-9faa-bfda521451fd</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.02</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>fcdd2c37-8128-4c3c-aa93-2a07fd289196</brickId>
                  <commentedOut>false</commentedOut>
                  <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#8.png" name="Kiblast (2)">
                    <isWebRequest>false</isWebRequest>
                    <valid>true</valid>
                  </look>
                </brick>
                <brick type="WaitBrick">
                  <brickId>98fd2aba-5415-45f2-b0e9-849d83eab473</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.02</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>9c53b4e6-2e4a-4fcc-b8b8-9cdbc2c655b5</brickId>
                  <commentedOut>false</commentedOut>
                  <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#9.png" name="Kiblast (3)">
                    <isWebRequest>false</isWebRequest>
                    <valid>true</valid>
                  </look>
                </brick>
                <brick type="ShowBrick">
                  <brickId>a6ea1713-06e6-4c62-bb91-ed0ddd90ce45</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
                <brick type="GoToBrick">
                  <brickId>5bf8a0f2-a237-4a19-b73c-4139a407bd5f</brickId>
                  <commentedOut>false</commentedOut>
                  <destinationSprite reference="../../../../../../../../scene[4]/objectList/object[4]"/>
                  <spinnerSelection>82</spinnerSelection>
                </brick>
                <brick type="PointToBrick">
                  <brickId>53db9087-fa5f-4625-843a-5f07f5f3009c</brickId>
                  <commentedOut>false</commentedOut>
                  <pointedObject reference="../../../../../../../../scene[4]/objectList/object[4]/scriptList/script/brickList/brick[4]/loopBricks/brick/pointedObject"/>
                </brick>
                <brick type="RepeatBrick">
                  <brickId>0bad9bc7-da37-4ee2-88c1-87c9916bd367</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIMES_TO_REPEAT">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>90</value>
                    </formula>
                  </formulaList>
                  <loopBricks>
                    <brick type="MoveNStepsBrick">
                      <brickId>0719fc7f-3a03-48c1-a5e1-b72bf1034e4d</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="STEPS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>20</value>
                        </formula>
                      </formulaList>
                    </brick>
                  </loopBricks>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>8fe67c25-f62e-4b09-9357-ea4147f1fdd2</scriptId>
              <receivedMessage>Kibast</receivedMessage>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Botão Gamehameha">
          <lookList/>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>81e18778-67ab-486b-b018-d5bbaf946cda</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>719</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>465</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>27c0c217-bad1-4f4c-989a-4b9c70f3ba7f</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>600</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>5d8cdd32-e750-4e7b-832f-d365e9879bb3</scriptId>
            </script>
            <script type="WhenScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="BroadcastBrick">
                  <brickId>e8d61f23-7e76-4b27-8965-3389a0bc729f</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Gamehameha</broadcastMessage>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>2a5dae8f-29f5-4ec2-89c6-d36ec3143df7</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>500</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="WaitBrick">
                  <brickId>4ee28bbe-9a6c-4636-b585-3dba52191ca7</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.2</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>6fd20355-9c79-4a73-8fdd-0a4d1713ad6d</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>600</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="HideBrick">
                  <brickId>8520f451-ced7-4abd-9278-1724a8856d51</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
                <brick type="WaitBrick">
                  <brickId>f9ec90e3-927c-478c-b34a-b6fee5d89740</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>5</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="ShowBrick">
                  <brickId>607171aa-1c78-4808-8bc6-074fda7b3c99</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>58c8a2aa-0ceb-48db-81e2-a79e517ab383</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Gamehameha">
          <lookList/>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ForeverBrick">
                  <brickId>ec85f3e0-0ac5-4721-942f-09c6af09fb6d</brickId>
                  <commentedOut>false</commentedOut>
                  <loopBricks>
                    <brick type="IfThenLogicBeginBrick">
                      <brickId>774189e7-9982-496c-a742-db9e57d95666</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="IF_CONDITION">
                          <additionalChildren/>
                          <leftChild>
                            <additionalChildren/>
                            <type>COLLISION_FORMULA</type>
                            <value>Vegeta</value>
                          </leftChild>
                          <rightChild>
                            <additionalChildren/>
                            <type>FUNCTION</type>
                            <value>TRUE</value>
                          </rightChild>
                          <type>OPERATOR</type>
                          <value>EQUAL</value>
                        </formula>
                      </formulaList>
                      <ifBranchBricks>
                        <brick type="ChangeVariableBrick">
                          <brickId>da80f0ae-12ec-436f-88b1-016544e8b7eb</brickId>
                          <commentedOut>false</commentedOut>
                          <formulaList>
                            <formula category="VARIABLE_CHANGE">
                              <additionalChildren/>
                              <rightChild>
                                <additionalChildren/>
                                <type>NUMBER</type>
                                <value>10</value>
                              </rightChild>
                              <type>OPERATOR</type>
                              <value>MINUS</value>
                            </formula>
                          </formulaList>
                          <userVariable reference="../../../../../../../../../../../../scene[4]/objectList/object[4]/scriptList/script[6]/brickList/brick/loopBricks/brick/ifBranchBricks/brick/userVariable"/>
                        </brick>
                        <brick type="ShowBrick">
                          <brickId>5cae31f9-65f4-436b-a4f5-934592fa5123</brickId>
                          <commentedOut>true</commentedOut>
                        </brick>
                        <brick type="HideBrick">
                          <brickId>7722f2a7-316d-4771-900d-b66c2c5c02c3</brickId>
                          <commentedOut>false</commentedOut>
                        </brick>
                      </ifBranchBricks>
                    </brick>
                  </loopBricks>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>bd177c17-3f4e-4517-8a41-74c55e738f08</scriptId>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ShowBrick">
                  <brickId>f5b5bff8-1ae2-4793-a036-417c6d4009ea</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
                <brick type="GoToBrick">
                  <brickId>0928e18f-2cf4-4f7f-b51b-224248bfc00a</brickId>
                  <commentedOut>false</commentedOut>
                  <destinationSprite reference="../../../../../../../../scene[4]/objectList/object[4]"/>
                  <spinnerSelection>82</spinnerSelection>
                </brick>
                <brick type="PointToBrick">
                  <brickId>425803b5-6911-47f6-8699-40e76050f715</brickId>
                  <commentedOut>false</commentedOut>
                  <pointedObject reference="../../../../../../../../scene[4]/objectList/object[4]/scriptList/script/brickList/brick[4]/loopBricks/brick/pointedObject"/>
                </brick>
                <brick type="RepeatBrick">
                  <brickId>803b8dd1-1053-49b4-ae82-22f278fcae08</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIMES_TO_REPEAT">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>90</value>
                    </formula>
                  </formulaList>
                  <loopBricks>
                    <brick type="MoveNStepsBrick">
                      <brickId>14d7fcb9-e69e-432e-885d-8ce5a2a40e69</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="STEPS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>250</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetSizeToBrick">
                      <brickId>f2f05cbf-0ce5-4673-a2c1-624671959f69</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="SIZE">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>350</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetLookBrick">
                      <brickId>c74be987-079a-4da2-af71-a91f3cb247d8</brickId>
                      <commentedOut>false</commentedOut>
                      <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#14.png" name="Gamehameha (1)">
                        <isWebRequest>false</isWebRequest>
                        <valid>true</valid>
                      </look>
                    </brick>
                    <brick type="WaitBrick">
                      <brickId>e97e6689-2c81-48e3-8008-2f71670bafdb</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="TIME_TO_WAIT_IN_SECONDS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>0.1</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetSizeToBrick">
                      <brickId>cb1ccb62-deaa-4415-b4ba-932b28700c7f</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="SIZE">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>500</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetLookBrick">
                      <brickId>764e106c-f4eb-499c-b7cc-4385d0e8f854</brickId>
                      <commentedOut>false</commentedOut>
                      <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#15.png" name="Gamehameha (2)">
                        <isWebRequest>false</isWebRequest>
                        <valid>true</valid>
                      </look>
                    </brick>
                    <brick type="WaitBrick">
                      <brickId>ae1dff9b-2d3c-48d3-affc-5f1e3571311c</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="TIME_TO_WAIT_IN_SECONDS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>0.2</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetSizeToBrick">
                      <brickId>a6cdb51f-80bb-4399-ae08-a175530e43c3</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="SIZE">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>450</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetLookBrick">
                      <brickId>ffd44ee7-3a5b-4714-89b7-986f06093255</brickId>
                      <commentedOut>false</commentedOut>
                      <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#16.png" name="Gamehameha (3)">
                        <isWebRequest>false</isWebRequest>
                        <valid>true</valid>
                      </look>
                    </brick>
                  </loopBricks>
                </brick>
                <brick type="WaitBrick">
                  <brickId>c721121c-7e2d-4dec-9aa7-505ac779c646</brickId>
                  <commentedOut>true</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.3</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>23fc189f-0191-4962-9ea7-13fa36208ec1</brickId>
                  <commentedOut>true</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>500</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>df195f09-57a9-4058-9789-6d30a21f84b9</scriptId>
              <receivedMessage>Gamehameha</receivedMessage>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Hitbox vegeta">
          <lookList/>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="HideBrick">
                  <brickId>0bf03fa7-464e-492e-8367-f69405df934d</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
                <brick type="ForeverBrick">
                  <brickId>ac80c248-5a72-4101-b972-1922d2bf5533</brickId>
                  <commentedOut>false</commentedOut>
                  <loopBricks>
                    <brick type="GoToBrick">
                      <brickId>f92ac763-c6d1-433a-86fa-dd16e1877499</brickId>
                      <commentedOut>false</commentedOut>
                      <spinnerSelection>80</spinnerSelection>
                    </brick>
                  </loopBricks>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>63eddeea-475d-4c77-ac1a-42417c791e4f</scriptId>
            </script>
            <script type="WhenConditionScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="BroadcastBrick">
                  <brickId>9e60f5ae-2595-4882-be49-4d596292a4d0</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Mortegoku</broadcastMessage>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>f6c73710-0fdd-48e9-8984-2c0d028549c0</scriptId>
              <formulaMap>
                <formula category="IF_CONDITION">
                  <additionalChildren/>
                  <leftChild>
                    <additionalChildren/>
                    <type>COLLISION_FORMULA</type>
                    <value>Goku</value>
                  </leftChild>
                  <rightChild>
                    <additionalChildren/>
                    <type>FUNCTION</type>
                    <value>TRUE</value>
                  </rightChild>
                  <type>OPERATOR</type>
                  <value>EQUAL</value>
                </formula>
              </formulaMap>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Barreira ">
          <lookList/>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>d7172f35-de9b-4c7e-96a7-d985d5736459</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>1207</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>46</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>e82fe14c-3ad1-4018-9335-c6bcb386c807</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>90</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>79435b04-2890-45cd-be1d-c09665ae3f15</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Barreira  (1)">
          <lookList/>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>a022227a-1db7-48a6-8688-ebf94aa6bd90</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>1210</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>3</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetTransparencyBrick">
                  <brickId>e5cc1a6f-0f22-45e4-b995-043aa834d7a8</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TRANSPARENCY">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>90</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>7d00ae02-58bb-4cb2-9fd5-e46be150355a</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Resetar">
          <lookList/>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>bc880180-270a-473d-8ca0-c34d9a913624</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>500</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>dd910416-5f74-4386-8e7e-c56353c0d1bb</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>500</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>1e8e7fc0-5802-4046-ad7f-7e9cd73b950b</scriptId>
            </script>
            <script type="WhenScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SceneStartBrick">
                  <brickId>8b519dd1-8ce6-4a27-9d8b-e70f941a7479</brickId>
                  <commentedOut>false</commentedOut>
                  <sceneToStart>Cutscene</sceneToStart>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>7c0ca941-7034-43c4-b015-e9577d2217c5</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
      </objectList>
    </scene>
    <scene>
      <name>Luta (2)</name>
      <objectList>
        <object type="Sprite" name="Fundo">
          <lookList>
            <look fileName="dragon-ball-z-championship-virtual-background-for-zoom (1).jpeg" name="dragon-ball-z-championship-virtual-background-for-zoom (1)">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetSizeToBrick">
                  <brickId>31c84c09-928a-4b3d-85be-9aaf51229608</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>150</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>2ca84b3e-a8d7-468e-ada8-4ea40a768936</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="&#xa;Direita">
          <lookList>
            <look fileName="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d.png" name="&#xa;Direita">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>b749a2f9-925e-4b31-af20-3f2780093ec9</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>720</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>422</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>33802d1d-92f7-4c10-927e-1c5c51ea9c2f</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>700</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetTransparencyBrick">
                  <brickId>87fccd7e-c892-4460-9616-20f27508d9b5</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TRANSPARENCY">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>20</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>98fbe5a5-6857-4c4d-84cb-0c14c52ba796</scriptId>
            </script>
            <script type="WhenScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetTransparencyBrick">
                  <brickId>66b98d21-6d21-492d-85eb-8082564f3354</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TRANSPARENCY">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>15</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="WaitBrick">
                  <brickId>3371c3bf-763f-4fcd-8e76-490181b33d3a</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.2</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetTransparencyBrick">
                  <brickId>526b1d7d-2295-4348-9cb4-269d69a70b0f</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TRANSPARENCY">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>20</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="BroadcastBrick">
                  <brickId>f3e3548e-ddba-4471-b6ae-d519cd486942</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Andar Direita</broadcastMessage>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>1f4e5937-fa72-4a92-9247-03fa996193a0</scriptId>
            </script>
            <script type="WhenScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="RepeatUntilBrick">
                  <brickId>86131284-15be-432a-b18b-efb203affc5f</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="REPEAT_UNTIL_CONDITION">
                      <additionalChildren/>
                      <leftChild>
                        <additionalChildren/>
                        <type>SENSOR</type>
                        <value>FINGER_TOUCHED</value>
                      </leftChild>
                      <rightChild>
                        <additionalChildren/>
                        <type>FUNCTION</type>
                        <value>FALSE</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>EQUAL</value>
                    </formula>
                  </formulaList>
                  <loopBricks>
                    <brick type="BroadcastBrick">
                      <brickId>d6b008c5-e8d9-4434-ae80-90320890cd19</brickId>
                      <commentedOut>false</commentedOut>
                      <broadcastMessage>Andar Direita</broadcastMessage>
                    </brick>
                  </loopBricks>
                </brick>
                <brick type="BroadcastBrick">
                  <brickId>7d00eaf1-da53-4331-a30f-2db0d02b592d</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Parar</broadcastMessage>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>f51b3f48-a067-4148-9028-dab9882930d6</scriptId>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="HideBrick">
                  <brickId>fea07ad7-0340-4c99-a8bd-9f76077d91b9</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>d7056709-02f0-4dd0-b8ba-f203b0b39202</scriptId>
              <receivedMessage>Mortegoku</receivedMessage>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Esquerda ">
          <lookList>
            <look fileName="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d_#0.png" name="&#xa;Direita">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>d429050e-7564-4ee3-93be-3f5c9134c60b</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>1064</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>420</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>2c0658e4-fde3-4e5b-a1a0-e9b7287b09f0</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>700</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetTransparencyBrick">
                  <brickId>967eebf2-a859-421b-9539-6a9c724dbdba</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TRANSPARENCY">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>20</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>bfcef38c-95cd-4e0e-a8bc-cbcad5afe553</scriptId>
            </script>
            <script type="WhenScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetTransparencyBrick">
                  <brickId>8c762628-6633-4884-b16e-5856f12c02fa</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TRANSPARENCY">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>15</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="WaitBrick">
                  <brickId>fe62afc7-60d2-4575-82a6-5403bc9a8c47</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.2</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetTransparencyBrick">
                  <brickId>c0ef520d-89c9-4ea2-a845-a7db55319fae</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TRANSPARENCY">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>20</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="BroadcastBrick">
                  <brickId>7a95a193-949f-4b4e-8389-6472de6948fa</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Andar Esquerda </broadcastMessage>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>484e4ae5-1af8-41be-ad5b-de54ff1326e1</scriptId>
            </script>
            <script type="WhenScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="RepeatUntilBrick">
                  <brickId>45adff53-7474-4adc-a1e3-c31939dff194</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="REPEAT_UNTIL_CONDITION">
                      <additionalChildren/>
                      <leftChild>
                        <additionalChildren/>
                        <type>SENSOR</type>
                        <value>FINGER_TOUCHED</value>
                      </leftChild>
                      <rightChild>
                        <additionalChildren/>
                        <type>FUNCTION</type>
                        <value>FALSE</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>EQUAL</value>
                    </formula>
                  </formulaList>
                  <loopBricks>
                    <brick type="BroadcastBrick">
                      <brickId>2a16d4ce-c902-4439-8535-c119174fcad2</brickId>
                      <commentedOut>false</commentedOut>
                      <broadcastMessage>Andar Esquerda </broadcastMessage>
                    </brick>
                  </loopBricks>
                </brick>
                <brick type="BroadcastBrick">
                  <brickId>a0ec9872-e88f-4d78-a697-e54b1b23af5e</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Parar</broadcastMessage>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>524bcd10-9422-472d-b82f-ec6178ca3911</scriptId>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="HideBrick">
                  <brickId>fd9515f3-1ec6-4793-be5b-c5a500cb7aef</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>349bfaea-3b64-4a12-a54c-7856a9c19897</scriptId>
              <receivedMessage>Mortegoku</receivedMessage>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Goku">
          <lookList>
            <look fileName="goku_black___ulsw_sprite_sheet_by_songoku0911_ddebcai.png" name="Parado">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_black___ulsw_sprite_sheet_by_songoku0911_ddebcai_#0.png" name="Direita ">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_black___ulsw_sprite_sheet_by_songoku0911_ddebcai_#1.png" name="Direita 2">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_black___ulsw_sprite_sheet_by_songoku0911_ddebcai_#2.png" name="Esquerda ">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_black___ulsw_sprite_sheet_by_songoku0911_ddebcai_#3.png" name="Esquerda 2">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_black___ulsw_sprite_sheet_by_songoku0911_ddebcai_#4.png" name="Soco 1">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_black___ulsw_sprite_sheet_by_songoku0911_ddebcai_#5.png" name="Soco 2">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_black___ulsw_sprite_sheet_by_songoku0911_ddebcai_#6.png" name="Soco 3">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_black___ulsw_sprite_sheet_by_songoku0911_ddebcai_#7.png" name="Soco 4">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_black___ulsw_sprite_sheet_by_songoku0911_ddebcai_#8.png" name="Soco 5">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_black___ulsw_sprite_sheet_by_songoku0911_ddebcai_#9.png" name="Soco 6">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_black___ulsw_sprite_sheet_by_songoku0911_ddebcai_#10.png" name="Kibast1">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_black___ulsw_sprite_sheet_by_songoku0911_ddebcai_#11.png" name="Kibast2">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_black___ulsw_sprite_sheet_by_songoku0911_ddebcai_#13.png" name="Morte 1">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_black___ulsw_sprite_sheet_by_songoku0911_ddebcai_#16.png" name="Morte 2">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_black___ulsw_sprite_sheet_by_songoku0911_ddebcai_#18.png" name="K1">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_black___ulsw_sprite_sheet_by_songoku0911_ddebcai_#19.png" name="K2">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_black___ulsw_sprite_sheet_by_songoku0911_ddebcai_#20.png" name="K3">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_black___ulsw_sprite_sheet_by_songoku0911_ddebcai_#21.png" name="K5">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_black___ulsw_sprite_sheet_by_songoku0911_ddebcai_#17.png" name="K6">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_black___ulsw_sprite_sheet_by_songoku0911_ddebcai_#22.png" name="K7">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_black___ulsw_sprite_sheet_by_songoku0911_ddebcai_#25.png" name="Tp 1">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_black___ulsw_sprite_sheet_by_songoku0911_ddebcai_#26.png" name="Tp 2">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_black___ulsw_sprite_sheet_by_songoku0911_ddebcai_#27.png" name="Tp 3">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="IfOnEdgeBounceBrick">
                  <brickId>69aab938-ac95-4ca2-b95f-81faadca44d8</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
                <brick type="PlaceAtBrick">
                  <brickId>734735ed-5c72-43ac-83c0-eb374e66be4b</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>1019</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>149</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>92e8df39-4f34-48ea-9ac6-9ae79df5f74e</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>550</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="ForeverBrick">
                  <brickId>870ab449-87b6-48bd-81c8-cb99d5833f84</brickId>
                  <commentedOut>false</commentedOut>
                  <loopBricks>
                    <brick type="PointToBrick">
                      <brickId>2e64913f-11a9-4d50-8d9e-896b5802fff1</brickId>
                      <commentedOut>false</commentedOut>
                      <pointedObject type="Sprite" name="Vegeta">
                        <lookList>
                          <look fileName="vegeta___ultimate_lsw_sheet_by_qsab101_dbzqwt5_#0.png" name="vegeta">
                            <isWebRequest>false</isWebRequest>
                            <valid>true</valid>
                          </look>
                          <look fileName="vegeta___ultimate_lsw_sheet_by_qsab101_dbzqwt5_#2.png" name="Voando">
                            <isWebRequest>false</isWebRequest>
                            <valid>true</valid>
                          </look>
                          <look fileName="vegeta___ultimate_lsw_sheet_by_qsab101_dbzqwt5.png" name="Soco 1">
                            <isWebRequest>false</isWebRequest>
                            <valid>true</valid>
                          </look>
                          <look fileName="vegeta___ultimate_lsw_sheet_by_qsab101_dbzqwt5_#1.png" name="Soco 2">
                            <isWebRequest>false</isWebRequest>
                            <valid>true</valid>
                          </look>
                          <look fileName="vegeta___ultimate_lsw_sheet_by_qsab101_dbzqwt5_#3.png" name="Soco 3">
                            <isWebRequest>false</isWebRequest>
                            <valid>true</valid>
                          </look>
                          <look fileName="vegeta___ultimate_lsw_sheet_by_qsab101_dbzqwt5_#4.png" name="Soco 4">
                            <isWebRequest>false</isWebRequest>
                            <valid>true</valid>
                          </look>
                          <look fileName="vegeta___ultimate_lsw_sheet_by_qsab101_dbzqwt5_#5.png" name="Soco 5">
                            <isWebRequest>false</isWebRequest>
                            <valid>true</valid>
                          </look>
                          <look fileName="vegeta___ultimate_lsw_sheet_by_qsab101_dbzqwt5_#6.png" name="Morte 1">
                            <isWebRequest>false</isWebRequest>
                            <valid>true</valid>
                          </look>
                          <look fileName="vegeta___ultimate_lsw_sheet_by_qsab101_dbzqwt5_#7.png" name="Morte 2">
                            <isWebRequest>false</isWebRequest>
                            <valid>true</valid>
                          </look>
                        </lookList>
                        <soundList/>
                        <scriptList>
                          <script type="StartScript" posX="0.0" posY="0.0">
                            <brickList>
                              <brick type="PlaceAtBrick">
                                <brickId>ee9d9ed2-c377-4c09-b7e8-4f7ec85f239e</brickId>
                                <commentedOut>false</commentedOut>
                                <formulaList>
                                  <formula category="X_POSITION">
                                    <additionalChildren/>
                                    <type>NUMBER</type>
                                    <value>744</value>
                                  </formula>
                                  <formula category="Y_POSITION">
                                    <additionalChildren/>
                                    <rightChild>
                                      <additionalChildren/>
                                      <type>NUMBER</type>
                                      <value>259</value>
                                    </rightChild>
                                    <type>OPERATOR</type>
                                    <value>MINUS</value>
                                  </formula>
                                </formulaList>
                              </brick>
                              <brick type="SetSizeToBrick">
                                <brickId>fc74c146-10d9-41cf-b95c-f9c4fbaebcd2</brickId>
                                <commentedOut>false</commentedOut>
                                <formulaList>
                                  <formula category="SIZE">
                                    <additionalChildren/>
                                    <type>NUMBER</type>
                                    <value>500</value>
                                  </formula>
                                </formulaList>
                              </brick>
                            </brickList>
                            <commentedOut>false</commentedOut>
                            <scriptId>e33433f5-cdb0-44ab-9489-aa97d808ae04</scriptId>
                          </script>
                          <script type="StartScript" posX="0.0" posY="0.0">
                            <brickList>
                              <brick type="ForeverBrick">
                                <brickId>d01feb92-7bd5-43d2-b716-5adb5d6d6cd8</brickId>
                                <commentedOut>false</commentedOut>
                                <loopBricks>
                                  <brick type="PointToBrick">
                                    <brickId>d8fc5eec-2dfb-4d3a-b98d-531e03dd2d70</brickId>
                                    <commentedOut>false</commentedOut>
                                    <pointedObject reference="../../../../../../../../../../../../../.."/>
                                  </brick>
                                  <brick type="SetRotationStyleBrick">
                                    <brickId>11ae7ff6-2da6-47bc-882c-c05663f23508</brickId>
                                    <commentedOut>false</commentedOut>
                                    <selection>0</selection>
                                  </brick>
                                </loopBricks>
                              </brick>
                            </brickList>
                            <commentedOut>false</commentedOut>
                            <scriptId>f8cc24b1-2657-4f7a-84c5-1bf2cad7a838</scriptId>
                          </script>
                          <script type="StartScript" posX="0.0" posY="0.0">
                            <brickList>
                              <brick type="ForeverBrick">
                                <brickId>52695ee0-2ebc-4b59-8922-06ba6e071975</brickId>
                                <commentedOut>false</commentedOut>
                                <loopBricks>
                                  <brick type="WaitBrick">
                                    <brickId>a3648d5d-bf43-4225-8601-c118ae421024</brickId>
                                    <commentedOut>false</commentedOut>
                                    <formulaList>
                                      <formula category="TIME_TO_WAIT_IN_SECONDS">
                                        <additionalChildren/>
                                        <type>NUMBER</type>
                                        <value>2</value>
                                      </formula>
                                    </formulaList>
                                  </brick>
                                  <brick type="RepeatUntilBrick">
                                    <brickId>6acd860e-b578-4a50-9ab5-5e0a8bb3887b</brickId>
                                    <commentedOut>false</commentedOut>
                                    <formulaList>
                                      <formula category="REPEAT_UNTIL_CONDITION">
                                        <additionalChildren/>
                                        <leftChild>
                                          <additionalChildren/>
                                          <type>COLLISION_FORMULA</type>
                                          <value>Goku</value>
                                        </leftChild>
                                        <rightChild>
                                          <additionalChildren/>
                                          <type>FUNCTION</type>
                                          <value>TRUE</value>
                                        </rightChild>
                                        <type>OPERATOR</type>
                                        <value>EQUAL</value>
                                      </formula>
                                    </formulaList>
                                    <loopBricks>
                                      <brick type="MoveNStepsBrick">
                                        <brickId>9ebd62b2-ea60-4042-ac11-29aa5fa1afa4</brickId>
                                        <commentedOut>false</commentedOut>
                                        <formulaList>
                                          <formula category="STEPS">
                                            <additionalChildren/>
                                            <type>NUMBER</type>
                                            <value>7</value>
                                          </formula>
                                        </formulaList>
                                      </brick>
                                      <brick type="SetLookBrick">
                                        <brickId>daa1a3ce-a9e2-4fc1-afd6-17268f8493a8</brickId>
                                        <commentedOut>false</commentedOut>
                                        <look reference="../../../../../../../../../lookList/look[2]"/>
                                      </brick>
                                    </loopBricks>
                                  </brick>
                                </loopBricks>
                              </brick>
                            </brickList>
                            <commentedOut>false</commentedOut>
                            <scriptId>8db06eaf-736f-4eab-bbb8-45dbd6b108ee</scriptId>
                          </script>
                          <script type="StartScript" posX="0.0" posY="0.0">
                            <brickList>
                              <brick type="ForeverBrick">
                                <brickId>27ac0f99-aa04-4116-929d-b8fd88c3cca2</brickId>
                                <commentedOut>false</commentedOut>
                                <loopBricks>
                                  <brick type="IfThenLogicBeginBrick">
                                    <brickId>30eaeda6-6b06-47f6-b4bf-6bbf21dda709</brickId>
                                    <commentedOut>false</commentedOut>
                                    <formulaList>
                                      <formula category="IF_CONDITION">
                                        <additionalChildren/>
                                        <leftChild>
                                          <additionalChildren/>
                                          <type>COLLISION_FORMULA</type>
                                          <value>Goku</value>
                                        </leftChild>
                                        <rightChild>
                                          <additionalChildren/>
                                          <type>FUNCTION</type>
                                          <value>TRUE</value>
                                        </rightChild>
                                        <type>OPERATOR</type>
                                        <value>EQUAL</value>
                                      </formula>
                                    </formulaList>
                                    <ifBranchBricks>
                                      <brick type="SetLookBrick">
                                        <brickId>3f15af3b-6660-4eaa-919a-a71f2c7812f7</brickId>
                                        <commentedOut>false</commentedOut>
                                        <look reference="../../../../../../../../../lookList/look[3]"/>
                                      </brick>
                                      <brick type="ChangeVariableBrick">
                                        <brickId>67f3912a-c526-4df5-9d14-609c9a7b917f</brickId>
                                        <commentedOut>false</commentedOut>
                                        <formulaList>
                                          <formula category="VARIABLE_CHANGE">
                                            <additionalChildren/>
                                            <rightChild>
                                              <additionalChildren/>
                                              <type>NUMBER</type>
                                              <value>1</value>
                                            </rightChild>
                                            <type>OPERATOR</type>
                                            <value>MINUS</value>
                                          </formula>
                                        </formulaList>
                                        <userVariable reference="../../../../../../../../../../../../../../../../../../../scene[4]/objectList/object[4]/scriptList/script/brickList/brick[4]/loopBricks/brick/pointedObject/scriptList/script[4]/brickList/brick/loopBricks/brick/ifBranchBricks/brick[2]/userVariable"/>
                                      </brick>
                                      <brick type="WaitBrick">
                                        <brickId>2343dad6-ddb3-4dd5-ad35-2577bb398af3</brickId>
                                        <commentedOut>false</commentedOut>
                                        <formulaList>
                                          <formula category="TIME_TO_WAIT_IN_SECONDS">
                                            <additionalChildren/>
                                            <type>NUMBER</type>
                                            <value>0.2</value>
                                          </formula>
                                        </formulaList>
                                      </brick>
                                      <brick type="SetLookBrick">
                                        <brickId>9899f114-4deb-4d0d-891d-69355578b58a</brickId>
                                        <commentedOut>false</commentedOut>
                                        <look reference="../../../../../../../../../lookList/look[4]"/>
                                      </brick>
                                      <brick type="ChangeVariableBrick">
                                        <brickId>20e76521-b433-4a98-907f-5d79ff3308fb</brickId>
                                        <commentedOut>false</commentedOut>
                                        <formulaList>
                                          <formula category="VARIABLE_CHANGE">
                                            <additionalChildren/>
                                            <rightChild>
                                              <additionalChildren/>
                                              <type>NUMBER</type>
                                              <value>1</value>
                                            </rightChild>
                                            <type>OPERATOR</type>
                                            <value>MINUS</value>
                                          </formula>
                                        </formulaList>
                                        <userVariable reference="../../../../../../../../../../../../../../../../../../../scene[4]/objectList/object[4]/scriptList/script/brickList/brick[4]/loopBricks/brick/pointedObject/scriptList/script[4]/brickList/brick/loopBricks/brick/ifBranchBricks/brick[2]/userVariable"/>
                                      </brick>
                                      <brick type="WaitBrick">
                                        <brickId>7c3ad025-1e39-4506-98ef-034cc350d37c</brickId>
                                        <commentedOut>false</commentedOut>
                                        <formulaList>
                                          <formula category="TIME_TO_WAIT_IN_SECONDS">
                                            <additionalChildren/>
                                            <type>NUMBER</type>
                                            <value>0.2</value>
                                          </formula>
                                        </formulaList>
                                      </brick>
                                      <brick type="SetLookBrick">
                                        <brickId>20e236b9-30cd-4d48-8d24-4b25de91f7ce</brickId>
                                        <commentedOut>false</commentedOut>
                                        <look reference="../../../../../../../../../lookList/look[5]"/>
                                      </brick>
                                      <brick type="ChangeVariableBrick">
                                        <brickId>f571ff06-4ca7-4204-8fa4-badf9e6a756b</brickId>
                                        <commentedOut>false</commentedOut>
                                        <formulaList>
                                          <formula category="VARIABLE_CHANGE">
                                            <additionalChildren/>
                                            <rightChild>
                                              <additionalChildren/>
                                              <type>NUMBER</type>
                                              <value>1</value>
                                            </rightChild>
                                            <type>OPERATOR</type>
                                            <value>MINUS</value>
                                          </formula>
                                        </formulaList>
                                        <userVariable reference="../../../../../../../../../../../../../../../../../../../scene[4]/objectList/object[4]/scriptList/script/brickList/brick[4]/loopBricks/brick/pointedObject/scriptList/script[4]/brickList/brick/loopBricks/brick/ifBranchBricks/brick[2]/userVariable"/>
                                      </brick>
                                      <brick type="WaitBrick">
                                        <brickId>634bcd34-3baa-435c-be19-80c49eea697f</brickId>
                                        <commentedOut>false</commentedOut>
                                        <formulaList>
                                          <formula category="TIME_TO_WAIT_IN_SECONDS">
                                            <additionalChildren/>
                                            <type>NUMBER</type>
                                            <value>0.2</value>
                                          </formula>
                                        </formulaList>
                                      </brick>
                                      <brick type="SetLookBrick">
                                        <brickId>b4dd218b-6762-4531-b341-0eb92706fa06</brickId>
                                        <commentedOut>false</commentedOut>
                                        <look reference="../../../../../../../../../lookList/look[6]"/>
                                      </brick>
                                      <brick type="ChangeVariableBrick">
                                        <brickId>2c0ffa15-7d28-457a-aca6-2390c09d6c55</brickId>
                                        <commentedOut>false</commentedOut>
                                        <formulaList>
                                          <formula category="VARIABLE_CHANGE">
                                            <additionalChildren/>
                                            <rightChild>
                                              <additionalChildren/>
                                              <type>NUMBER</type>
                                              <value>1</value>
                                            </rightChild>
                                            <type>OPERATOR</type>
                                            <value>MINUS</value>
                                          </formula>
                                        </formulaList>
                                        <userVariable reference="../../../../../../../../../../../../../../../../../../../scene[4]/objectList/object[4]/scriptList/script/brickList/brick[4]/loopBricks/brick/pointedObject/scriptList/script[4]/brickList/brick/loopBricks/brick/ifBranchBricks/brick[2]/userVariable"/>
                                      </brick>
                                      <brick type="WaitBrick">
                                        <brickId>ada4824e-9003-4afe-82af-cf915f16ac62</brickId>
                                        <commentedOut>false</commentedOut>
                                        <formulaList>
                                          <formula category="TIME_TO_WAIT_IN_SECONDS">
                                            <additionalChildren/>
                                            <type>NUMBER</type>
                                            <value>0.2</value>
                                          </formula>
                                        </formulaList>
                                      </brick>
                                      <brick type="SetLookBrick">
                                        <brickId>6bbf734c-010c-418b-be99-076152d30494</brickId>
                                        <commentedOut>false</commentedOut>
                                        <look reference="../../../../../../../../../lookList/look[7]"/>
                                      </brick>
                                      <brick type="ChangeVariableBrick">
                                        <brickId>ce2a0fb7-eaec-4c9f-94cb-7143eb0f8b38</brickId>
                                        <commentedOut>false</commentedOut>
                                        <formulaList>
                                          <formula category="VARIABLE_CHANGE">
                                            <additionalChildren/>
                                            <rightChild>
                                              <additionalChildren/>
                                              <type>NUMBER</type>
                                              <value>8</value>
                                            </rightChild>
                                            <type>OPERATOR</type>
                                            <value>MINUS</value>
                                          </formula>
                                        </formulaList>
                                        <userVariable reference="../../../../../../../../../../../../../../../../../../../scene[4]/objectList/object[4]/scriptList/script/brickList/brick[4]/loopBricks/brick/pointedObject/scriptList/script[4]/brickList/brick/loopBricks/brick/ifBranchBricks/brick[2]/userVariable"/>
                                      </brick>
                                    </ifBranchBricks>
                                  </brick>
                                </loopBricks>
                              </brick>
                            </brickList>
                            <commentedOut>false</commentedOut>
                            <scriptId>e12aa85d-beb0-4d14-a995-bc69aaabc1f9</scriptId>
                          </script>
                          <script type="BroadcastScript" posX="0.0" posY="0.0">
                            <brickList>
                              <brick type="HideBrick">
                                <brickId>8bc178bf-f5fd-46df-993a-741aa196a49e</brickId>
                                <commentedOut>false</commentedOut>
                              </brick>
                            </brickList>
                            <commentedOut>false</commentedOut>
                            <scriptId>d5c569d9-9399-4173-bc41-0823e63a5853</scriptId>
                            <receivedMessage>Sumirvegeta</receivedMessage>
                          </script>
                          <script type="BroadcastScript" posX="0.0" posY="0.0">
                            <brickList>
                              <brick type="RepeatBrick">
                                <brickId>d61e4670-5bd0-48aa-8f1b-c339eab1e350</brickId>
                                <commentedOut>false</commentedOut>
                                <formulaList>
                                  <formula category="TIMES_TO_REPEAT">
                                    <additionalChildren/>
                                    <type>NUMBER</type>
                                    <value>100</value>
                                  </formula>
                                </formulaList>
                                <loopBricks>
                                  <brick type="SetLookBrick">
                                    <brickId>51bcdc2d-a81f-435a-8ebc-be00a531f8f4</brickId>
                                    <commentedOut>false</commentedOut>
                                    <look reference="../../../../../../../lookList/look[8]"/>
                                  </brick>
                                  <brick type="WaitBrick">
                                    <brickId>e2309053-e700-45a0-b042-d75cdf14d177</brickId>
                                    <commentedOut>false</commentedOut>
                                    <formulaList>
                                      <formula category="TIME_TO_WAIT_IN_SECONDS">
                                        <additionalChildren/>
                                        <type>NUMBER</type>
                                        <value>0.3</value>
                                      </formula>
                                    </formulaList>
                                  </brick>
                                  <brick type="SetLookBrick">
                                    <brickId>0ab3cfde-f148-4f82-ae39-6f8131ef37ce</brickId>
                                    <commentedOut>false</commentedOut>
                                    <look reference="../../../../../../../lookList/look[9]"/>
                                  </brick>
                                </loopBricks>
                              </brick>
                            </brickList>
                            <commentedOut>false</commentedOut>
                            <scriptId>5618f8e1-ff56-4cb4-847f-1c5468c77d00</scriptId>
                            <receivedMessage>Morte vegeta</receivedMessage>
                          </script>
                          <script type="BroadcastScript" posX="0.0" posY="0.0">
                            <brickList>
                              <brick type="SetLookBrick">
                                <brickId>53e11345-2e95-4bee-8d5e-d3f922a04f3f</brickId>
                                <commentedOut>false</commentedOut>
                                <look reference="../../../../../lookList/look[8]"/>
                              </brick>
                              <brick type="WaitBrick">
                                <brickId>a78a3f15-3d73-495c-a169-dfadf9821380</brickId>
                                <commentedOut>false</commentedOut>
                                <formulaList>
                                  <formula category="TIME_TO_WAIT_IN_SECONDS">
                                    <additionalChildren/>
                                    <type>NUMBER</type>
                                    <value>2</value>
                                  </formula>
                                </formulaList>
                              </brick>
                              <brick type="SetLookBrick">
                                <brickId>f7deab7f-4234-451c-aa70-f3dd18a03a11</brickId>
                                <commentedOut>false</commentedOut>
                                <look reference="../../../../../lookList/look[8]"/>
                              </brick>
                              <brick type="ChangeXByNBrick">
                                <brickId>2ae1adba-0509-4d31-bbfd-22c39d8fc3f5</brickId>
                                <commentedOut>false</commentedOut>
                                <formulaList>
                                  <formula category="X_POSITION_CHANGE">
                                    <additionalChildren/>
                                    <rightChild>
                                      <additionalChildren/>
                                      <type>NUMBER</type>
                                      <value>30</value>
                                    </rightChild>
                                    <type>OPERATOR</type>
                                    <value>MINUS</value>
                                  </formula>
                                </formulaList>
                              </brick>
                            </brickList>
                            <commentedOut>false</commentedOut>
                            <scriptId>13c860ac-0009-4bb0-89be-335c62a9d3dd</scriptId>
                            <receivedMessage>Acerto vegeta</receivedMessage>
                          </script>
                        </scriptList>
                        <nfcTagList/>
                        <userVariables/>
                        <userLists/>
                        <userDefinedBrickList/>
                      </pointedObject>
                    </brick>
                    <brick type="SetRotationStyleBrick">
                      <brickId>b4f7bef1-99ee-4972-9a3b-a1abc288ab78</brickId>
                      <commentedOut>false</commentedOut>
                      <selection>0</selection>
                    </brick>
                  </loopBricks>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>569d38bb-1c89-4537-ad2a-3770356fd58e</scriptId>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ChangeXByNBrick">
                  <brickId>b8142341-cdd8-4529-8145-08160947e856</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION_CHANGE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.5</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>d71cb167-7bca-41c2-9a5c-8e855406e569</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[2]"/>
                </brick>
                <brick type="WaitBrick">
                  <brickId>86521f5b-65a4-41f5-a7df-6757919d61ba</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.001</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>3f89cf33-d280-4f60-b86f-9b084210dd39</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[3]"/>
                </brick>
                <brick type="WaitBrick">
                  <brickId>ba4a6c5c-2489-49d7-964b-d77241690de0</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.001</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>9cdb8d71-6907-4970-b13c-1aeaa2bf8048</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look"/>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>01c63e06-6536-47cd-a395-14a8eb7a49b6</scriptId>
              <receivedMessage>Andar Direita</receivedMessage>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetLookBrick">
                  <brickId>6a882fd4-79cd-496d-b19f-9de5f01d3b30</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look"/>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>4faef8be-eec8-4577-9a36-f98dac592eb5</scriptId>
              <receivedMessage>Parar</receivedMessage>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ChangeXByNBrick">
                  <brickId>993dc6c3-9753-455d-a9be-57b141392a53</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION_CHANGE">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>0.5</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>9138fb0f-88e4-4002-94c3-3b0707521fbe</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[2]"/>
                </brick>
                <brick type="WaitBrick">
                  <brickId>40a49114-ba7c-4d50-91d1-b1873d18093d</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.1</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>a34758f8-dd4e-437e-8f88-4c121d7befdd</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look"/>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>2bd1c92a-d58e-4a82-b739-409e03c4eae6</brickId>
                  <commentedOut>true</commentedOut>
                  <look reference="../../../../../lookList/look[4]"/>
                </brick>
                <brick type="WaitBrick">
                  <brickId>f3c4f2f0-65b1-4a34-bb93-f17f1966e8ba</brickId>
                  <commentedOut>true</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.1</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>6eeed3e9-4ba4-4721-b85f-d227306f4214</brickId>
                  <commentedOut>true</commentedOut>
                  <look reference="../../../../../lookList/look[5]"/>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>04ec9e37-ca4e-4b35-9ec5-d6b0a4b4b394</scriptId>
              <receivedMessage>Andar Esquerda </receivedMessage>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetLookBrick">
                  <brickId>c8119cb9-a35c-4331-a1d5-ddcb67ad5f7a</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[6]"/>
                </brick>
                <brick type="WaitBrick">
                  <brickId>46329e57-1268-473a-92b4-f01d70a89070</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.1</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>8041b158-5505-4704-b657-18b7e4494582</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[7]"/>
                </brick>
                <brick type="WaitBrick">
                  <brickId>d616e5d9-c423-4805-a408-fd34b9601d8e</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.01</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>37060655-7457-40c5-bf08-7bc9bbededb0</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[8]"/>
                </brick>
                <brick type="WaitBrick">
                  <brickId>0c9416d3-53fd-4ff0-994d-8586adc62726</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.01</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>55b39c8b-2014-4ea8-9881-6761c64e0edd</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[9]"/>
                </brick>
                <brick type="WaitBrick">
                  <brickId>62e6185a-1aca-460a-8425-1f095a3860e7</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.01</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>e9a34b56-21fa-4656-b6e1-e5724fdf37e5</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[10]"/>
                </brick>
                <brick type="WaitBrick">
                  <brickId>faf892c0-a14d-4e8f-8857-8107840f5ab5</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.01</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>8d322fbc-57b6-4f7d-b569-1fc33d4a097e</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[11]"/>
                </brick>
                <brick type="WaitBrick">
                  <brickId>04ff4a0f-48e5-4412-99a2-21a40b09d2f9</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.01</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>8ba3249a-7733-4551-ac89-f0c2eb30f0f6</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look"/>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>2665ce93-2c15-4d7e-ad9e-76a021ccfe44</scriptId>
              <receivedMessage>Soco</receivedMessage>
            </script>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ForeverBrick">
                  <brickId>d9f08cd9-0bc7-4e00-a264-1deab05361ae</brickId>
                  <commentedOut>true</commentedOut>
                  <loopBricks>
                    <brick type="IfThenLogicBeginBrick">
                      <brickId>cb905dfb-627a-410f-8723-510be7fabce1</brickId>
                      <commentedOut>true</commentedOut>
                      <formulaList>
                        <formula category="IF_CONDITION">
                          <additionalChildren/>
                          <leftChild>
                            <additionalChildren/>
                            <type>COLLISION_FORMULA</type>
                            <value>Vegeta</value>
                          </leftChild>
                          <rightChild>
                            <additionalChildren/>
                            <type>FUNCTION</type>
                            <value>TRUE</value>
                          </rightChild>
                          <type>OPERATOR</type>
                          <value>EQUAL</value>
                        </formula>
                      </formulaList>
                      <ifBranchBricks>
                        <brick type="ChangeVariableBrick">
                          <brickId>c91eb88b-89f2-4fb2-bb0d-708a5ec0ac10</brickId>
                          <commentedOut>true</commentedOut>
                          <formulaList>
                            <formula category="VARIABLE_CHANGE">
                              <additionalChildren/>
                              <rightChild>
                                <additionalChildren/>
                                <type>NUMBER</type>
                                <value>1</value>
                              </rightChild>
                              <type>OPERATOR</type>
                              <value>MINUS</value>
                            </formula>
                          </formulaList>
                          <userVariable reference="../../../../../../../../../../../../scene[4]/objectList/object[4]/scriptList/script[6]/brickList/brick/loopBricks/brick/ifBranchBricks/brick/userVariable"/>
                        </brick>
                        <brick type="WaitBrick">
                          <brickId>acdfdc46-30a9-460f-ba56-85ee67ce77e1</brickId>
                          <commentedOut>true</commentedOut>
                          <formulaList>
                            <formula category="TIME_TO_WAIT_IN_SECONDS">
                              <additionalChildren/>
                              <type>NUMBER</type>
                              <value>0.2</value>
                            </formula>
                          </formulaList>
                        </brick>
                        <brick type="ChangeVariableBrick">
                          <brickId>3b15d618-3c28-47aa-b21d-9eb1dee89fa9</brickId>
                          <commentedOut>true</commentedOut>
                          <formulaList>
                            <formula category="VARIABLE_CHANGE">
                              <additionalChildren/>
                              <rightChild>
                                <additionalChildren/>
                                <type>NUMBER</type>
                                <value>1</value>
                              </rightChild>
                              <type>OPERATOR</type>
                              <value>MINUS</value>
                            </formula>
                          </formulaList>
                          <userVariable reference="../../../../../../../../../../../../scene[4]/objectList/object[4]/scriptList/script[6]/brickList/brick/loopBricks/brick/ifBranchBricks/brick/userVariable"/>
                        </brick>
                        <brick type="WaitBrick">
                          <brickId>6cbd06e3-8598-4a18-a94f-0b6d1f3bf5f8</brickId>
                          <commentedOut>true</commentedOut>
                          <formulaList>
                            <formula category="TIME_TO_WAIT_IN_SECONDS">
                              <additionalChildren/>
                              <type>NUMBER</type>
                              <value>0.2</value>
                            </formula>
                          </formulaList>
                        </brick>
                        <brick type="ChangeVariableBrick">
                          <brickId>aa33c495-aa5d-41d6-a110-38799ec1ac21</brickId>
                          <commentedOut>true</commentedOut>
                          <formulaList>
                            <formula category="VARIABLE_CHANGE">
                              <additionalChildren/>
                              <rightChild>
                                <additionalChildren/>
                                <type>NUMBER</type>
                                <value>1</value>
                              </rightChild>
                              <type>OPERATOR</type>
                              <value>MINUS</value>
                            </formula>
                          </formulaList>
                          <userVariable reference="../../../../../../../../../../../../scene[4]/objectList/object[4]/scriptList/script[6]/brickList/brick/loopBricks/brick/ifBranchBricks/brick/userVariable"/>
                        </brick>
                        <brick type="WaitBrick">
                          <brickId>3ede4d70-89e1-4477-bea1-da55b4c4eb31</brickId>
                          <commentedOut>true</commentedOut>
                          <formulaList>
                            <formula category="TIME_TO_WAIT_IN_SECONDS">
                              <additionalChildren/>
                              <type>NUMBER</type>
                              <value>0.2</value>
                            </formula>
                          </formulaList>
                        </brick>
                        <brick type="ChangeVariableBrick">
                          <brickId>ef8970b9-cf26-4feb-aff6-eb763f946ebf</brickId>
                          <commentedOut>true</commentedOut>
                          <formulaList>
                            <formula category="VARIABLE_CHANGE">
                              <additionalChildren/>
                              <rightChild>
                                <additionalChildren/>
                                <type>NUMBER</type>
                                <value>1</value>
                              </rightChild>
                              <type>OPERATOR</type>
                              <value>MINUS</value>
                            </formula>
                          </formulaList>
                          <userVariable reference="../../../../../../../../../../../../scene[4]/objectList/object[4]/scriptList/script[6]/brickList/brick/loopBricks/brick/ifBranchBricks/brick/userVariable"/>
                        </brick>
                        <brick type="WaitBrick">
                          <brickId>68b000cf-a918-4b1d-bd3a-fad3a7f86e67</brickId>
                          <commentedOut>true</commentedOut>
                          <formulaList>
                            <formula category="TIME_TO_WAIT_IN_SECONDS">
                              <additionalChildren/>
                              <type>NUMBER</type>
                              <value>0.2</value>
                            </formula>
                          </formulaList>
                        </brick>
                        <brick type="ChangeVariableBrick">
                          <brickId>0917471c-4380-4abf-95f9-a8c822c26070</brickId>
                          <commentedOut>true</commentedOut>
                          <formulaList>
                            <formula category="VARIABLE_CHANGE">
                              <additionalChildren/>
                              <rightChild>
                                <additionalChildren/>
                                <type>NUMBER</type>
                                <value>1</value>
                              </rightChild>
                              <type>OPERATOR</type>
                              <value>MINUS</value>
                            </formula>
                          </formulaList>
                          <userVariable reference="../../../../../../../../../../../../scene[4]/objectList/object[4]/scriptList/script[6]/brickList/brick/loopBricks/brick/ifBranchBricks/brick/userVariable"/>
                        </brick>
                      </ifBranchBricks>
                    </brick>
                  </loopBricks>
                </brick>
              </brickList>
              <commentedOut>true</commentedOut>
              <scriptId>7b9c8df7-ea97-4cf5-af60-4578afc8afc7</scriptId>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetLookBrick">
                  <brickId>872182e3-6c6f-44c9-8d03-4e7e3d513f99</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[12]"/>
                </brick>
                <brick type="WaitBrick">
                  <brickId>4a5487a5-1a3e-441c-9e99-f29507a1d80e</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.1</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>ad257471-0af2-41ed-b0b7-29ae1ae323df</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[13]"/>
                </brick>
                <brick type="WaitBrick">
                  <brickId>fad07666-ab03-47a9-87f6-418f9aa94e2c</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.1</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>995d0ff4-7b7b-4f58-aa49-1fdc4b0b72d9</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look"/>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>f7ce7a3b-f834-4439-b684-57ca82275720</scriptId>
              <receivedMessage>Kibast</receivedMessage>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetLookBrick">
                  <brickId>97a4decb-d41c-45e7-9ee7-02f135a3dfaa</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[14]"/>
                </brick>
                <brick type="WaitBrick">
                  <brickId>832d6ba9-9894-4d9c-827b-d19727b9cd33</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.5</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>778206e6-84e8-4341-a0b8-6c93db75a27f</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[15]"/>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>0f44b0df-6c3f-4c4c-8c2f-7ce52169a171</scriptId>
              <receivedMessage>Mortegoku</receivedMessage>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="HideBrick">
                  <brickId>0bda1d60-1d05-4a04-a9a4-adeb01a90da8</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>e3dab6cc-9bc5-4e0b-8530-881e9afba8af</scriptId>
              <receivedMessage>Sumir goku</receivedMessage>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetLookBrick">
                  <brickId>09156c69-4ec9-4401-b106-d79b29032b44</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[12]"/>
                </brick>
                <brick type="WaitBrick">
                  <brickId>51235f01-1b61-4bc5-be03-79e4c037c886</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.1</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>aad544e9-a189-4dc8-ab80-31aa19fcf808</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look"/>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>c8217982-b410-46e5-bc49-a22a4411bf0a</scriptId>
              <receivedMessage>Gamehameha</receivedMessage>
            </script>
            <script type="WhenConditionScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ChangeXByNBrick">
                  <brickId>55f6db8a-a8f7-4f74-ab29-3aded1aba011</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION_CHANGE">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>10</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>19438261-a1e0-4a20-a08d-07b722aaab21</scriptId>
              <formulaMap>
                <formula category="IF_CONDITION">
                  <additionalChildren/>
                  <leftChild>
                    <additionalChildren/>
                    <type>COLLISION_FORMULA</type>
                    <value>Barreira </value>
                  </leftChild>
                  <rightChild>
                    <additionalChildren/>
                    <type>FUNCTION</type>
                    <value>TRUE</value>
                  </rightChild>
                  <type>OPERATOR</type>
                  <value>EQUAL</value>
                </formula>
              </formulaMap>
            </script>
            <script type="WhenConditionScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ChangeXByNBrick">
                  <brickId>ad8e32aa-0db9-489e-830c-3a958283b906</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION_CHANGE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>10</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>318b5d2c-496a-4d15-b0ae-d9702e5ce9fe</scriptId>
              <formulaMap>
                <formula category="IF_CONDITION">
                  <additionalChildren/>
                  <leftChild>
                    <additionalChildren/>
                    <type>COLLISION_FORMULA</type>
                    <value>Barreira  (1)</value>
                  </leftChild>
                  <rightChild>
                    <additionalChildren/>
                    <type>FUNCTION</type>
                    <value>TRUE</value>
                  </rightChild>
                  <type>OPERATOR</type>
                  <value>EQUAL</value>
                </formula>
              </formulaMap>
            </script>
            <script type="WhenConditionScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ChangeXByNBrick">
                  <brickId>48b7ae8d-3767-4237-b5a7-fdaefba8681c</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION_CHANGE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>10</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>efe2665e-38c5-4954-b855-e5f69f42472d</scriptId>
              <formulaMap>
                <formula category="IF_CONDITION">
                  <additionalChildren/>
                  <leftChild>
                    <additionalChildren/>
                    <type>SENSOR</type>
                    <value>COLLIDES_WITH_EDGE</value>
                  </leftChild>
                  <rightChild>
                    <additionalChildren/>
                    <type>FUNCTION</type>
                    <value>TRUE</value>
                  </rightChild>
                  <type>OPERATOR</type>
                  <value>EQUAL</value>
                </formula>
              </formulaMap>
            </script>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ForeverBrick">
                  <brickId>e8287175-a57f-4609-a24f-a6c4d9cb7c4e</brickId>
                  <commentedOut>false</commentedOut>
                  <loopBricks>
                    <brick type="IfOnEdgeBounceBrick">
                      <brickId>c2791d20-aeac-4628-922e-fef608234228</brickId>
                      <commentedOut>false</commentedOut>
                    </brick>
                  </loopBricks>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>c8f6d372-0d9c-431f-912b-7b62e6f04c37</scriptId>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetLookBrick">
                  <brickId>6260c4b3-b5c5-4d05-8714-f75b28b727a1</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[16]"/>
                </brick>
                <brick type="WaitBrick">
                  <brickId>7df98892-5556-4ada-9c6e-a0782af0198f</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.1</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>3bbebeea-77d3-4dee-97f2-659beca32b9f</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[17]"/>
                </brick>
                <brick type="WaitBrick">
                  <brickId>c0395409-8978-44b7-b67f-65b529718e3e</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.1</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>31c97673-8dfe-43a6-b07d-60d2d5623c05</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[18]"/>
                </brick>
                <brick type="WaitBrick">
                  <brickId>ad73c5c4-ed25-46dd-a595-d4441ccccf83</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.1</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>c5e1ec4c-296e-4f04-8ec6-dc35c8bf4888</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[19]"/>
                </brick>
                <brick type="WaitBrick">
                  <brickId>5a3de64f-6763-4e2c-bafd-d63d27d471e9</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.1</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>b7ea4b0f-f833-4349-815d-8420aadc64d2</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[20]"/>
                </brick>
                <brick type="WaitBrick">
                  <brickId>4ec6bf5b-6763-4e0f-a3cf-97529da90649</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.1</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>5e563d99-ce12-4dec-b9be-eb618f98e922</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[21]"/>
                </brick>
                <brick type="WaitBrick">
                  <brickId>ad30d69d-00ef-482d-a1c5-efaf54eb79e4</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.1</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>468d1208-c465-4a95-ad82-0cc884116515</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look"/>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>d253f6d0-64de-4110-9982-ef70f07eedb9</scriptId>
              <receivedMessage>KH</receivedMessage>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="MoveNStepsBrick">
                  <brickId>ed96b59b-d245-4990-bd87-1d0082663dde</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="STEPS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>800</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>47073668-81bc-4fbe-8ee7-85fe134f5c03</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[22]"/>
                </brick>
                <brick type="WaitBrick">
                  <brickId>699f8724-2fbf-41f5-bd1a-5c5ac4c0384a</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.1</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>47f13ff9-11e9-43da-9609-39a18910910a</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[23]"/>
                </brick>
                <brick type="WaitBrick">
                  <brickId>eb3a7a90-9b64-4d2c-b4a9-697b3d46f15e</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.1</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>28210091-3f95-47d7-88a4-2132c9523c8a</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[24]"/>
                </brick>
                <brick type="WaitBrick">
                  <brickId>878af65c-5b7a-4ac7-a297-7a9aea5a96bf</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.1</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>74447536-7654-426d-b3a0-fd8fbd3cd445</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[22]"/>
                </brick>
                <brick type="WaitBrick">
                  <brickId>7c3a5aeb-d0e9-4300-979f-2d146771a477</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.1</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>8e7a03cf-cacc-4aa7-a9f4-74a6da2b5248</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look"/>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>69d0e1c9-a90a-4a04-9e91-54eccb1a6edd</scriptId>
              <receivedMessage>Tp</receivedMessage>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="MoveNStepsBrick">
                  <brickId>98181df1-9de7-4360-a5ff-178154a5ac70</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="STEPS">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>400</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>4ec3e8b0-9118-4fff-971b-c3283e2f7b65</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[22]"/>
                </brick>
                <brick type="WaitBrick">
                  <brickId>07b0dee4-7364-403f-bf41-ef91869f8a3a</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.1</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>3fca494e-4779-439c-a34e-8a211cee0a16</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[23]"/>
                </brick>
                <brick type="WaitBrick">
                  <brickId>60c2c8d5-6a04-4567-840d-15aa9185c58a</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.1</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>2bee24f3-aca6-41af-8238-a8cde64b1a58</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[24]"/>
                </brick>
                <brick type="WaitBrick">
                  <brickId>c1a119a5-3863-406d-953a-21229a594925</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.1</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>6c1988db-664e-4ffe-a30b-906840a5de89</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[22]"/>
                </brick>
                <brick type="WaitBrick">
                  <brickId>67aac0d3-5191-46c7-89f0-834ac7dab34c</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.1</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>01a554cc-7657-4709-8d1a-b5f9cfbde29c</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look"/>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>aea22370-09e3-4630-aa9d-4394fca3bba0</scriptId>
              <receivedMessage>Tp 2</receivedMessage>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object reference="../object[4]/scriptList/script/brickList/brick[4]/loopBricks/brick/pointedObject"/>
        <object type="Sprite" name="&#xa;Soco">
          <lookList>
            <look fileName="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d_#1.png" name="&#xa;Soco">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>dfa60b32-c03e-40ca-b9f3-53acc586fc23</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>1088</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>460</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>009401e5-8a1a-4687-8837-6b1de0f9577b</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>600</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>42331bbb-9b45-4fe2-9b62-c999fa323e7d</scriptId>
            </script>
            <script type="WhenScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetSizeToBrick">
                  <brickId>31c9475a-11f1-4b6b-839e-198fe544cff4</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>500</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="WaitBrick">
                  <brickId>a9ab827d-e5d0-42fe-a00a-e3c409d03be7</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.2</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>048aaba0-9b7a-4314-82cf-766443c4bb94</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>600</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="BroadcastBrick">
                  <brickId>707d319b-1539-4d0e-bbb2-16930cc5fe34</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Soco</broadcastMessage>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>b386fa63-caf8-4b3b-be9f-6d7b85fc09bd</scriptId>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="HideBrick">
                  <brickId>bf900510-7cd9-4998-9871-d9a357c07206</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>7495cf1f-e51a-425c-acfd-c09f29125454</scriptId>
              <receivedMessage>Mortegoku</receivedMessage>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Vida goku">
          <lookList>
            <look fileName="imagesss (2)_#0.png" name="Vida 1">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="imagesss (2)_#1.png" name="Vida 2">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="imagesss (2)_#2.png" name="Vida 3">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="imagesss (2)_#4.png" name="Vida 4">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="imagesss (2)_#3.png" name="Vida 5">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="imagesss (2)_#5.png" name="Vida 6">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>ac0fe541-bb5d-4671-b92a-9b9d269b7232</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>769</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>451</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>f4823a1f-a75e-4749-b21f-eeda30cb0bdb</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>400</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetVariableBrick">
                  <brickId>2cf95a35-9c3d-4fc6-8c56-14e6053c1190</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="VARIABLE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>100</value>
                    </formula>
                  </formulaList>
                  <userVariable reference="../../../../../../../../scene[4]/objectList/object[4]/scriptList/script/brickList/brick[4]/loopBricks/brick/pointedObject/scriptList/script[4]/brickList/brick/loopBricks/brick/ifBranchBricks/brick[2]/userVariable"/>
                </brick>
                <brick type="ShowTextBrick">
                  <brickId>c20805c2-9a2f-4544-9425-6cb707b0d658</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>400</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>571</value>
                    </formula>
                  </formulaList>
                  <userVariable reference="../../../../../../../../scene[4]/objectList/object[4]/scriptList/script/brickList/brick[4]/loopBricks/brick/pointedObject/scriptList/script[4]/brickList/brick/loopBricks/brick/ifBranchBricks/brick[2]/userVariable"/>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>cc11939d-f9a5-4aa1-a9a2-d2869793c0cd</scriptId>
            </script>
            <script type="WhenConditionScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="BroadcastBrick">
                  <brickId>c711aa80-2db1-4e65-802e-582652a8f94e</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Sumirvegeta</broadcastMessage>
                </brick>
                <brick type="BroadcastBrick">
                  <brickId>9e62f99a-ee25-4da4-bd70-e609d63ee52b</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Mortegoku</broadcastMessage>
                </brick>
                <brick type="WaitBrick">
                  <brickId>c61b8625-3dcb-4e89-8c34-c1f1685332d0</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>3</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SceneStartBrick">
                  <brickId>c31f824e-db77-4abc-bad2-a2c7a6c28774</brickId>
                  <commentedOut>false</commentedOut>
                  <sceneToStart>Game over</sceneToStart>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>af93a318-b0ba-4216-87f2-e7fc31ba59d9</scriptId>
              <formulaMap>
                <formula category="IF_CONDITION">
                  <additionalChildren/>
                  <leftChild>
                    <additionalChildren/>
                    <type>USER_VARIABLE</type>
                    <value>Vida_Goku</value>
                  </leftChild>
                  <rightChild>
                    <additionalChildren/>
                    <rightChild>
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>1</value>
                    </rightChild>
                    <type>OPERATOR</type>
                    <value>MINUS</value>
                  </rightChild>
                  <type>OPERATOR</type>
                  <value>SMALLER_THAN</value>
                </formula>
              </formulaMap>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Vida bot">
          <lookList>
            <look fileName="imagesss (2)_#6.png" name="Vida 1">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="imagesss (2)_#7.png" name="Vida 2">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="imagesss (2)_#8.png" name="Vida 3">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="imagesss (2)_#9.png" name="Vida 4">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="imagesss (2)_#10.png" name="Vida 5">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="imagesss (2)_#11.png" name="Vida 6">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>b93494f2-2f19-4fd8-8c5d-397045cabd3e</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>770</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>440</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>b68ce061-c51c-464b-b642-93399a0d8d87</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>400</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetVariableBrick">
                  <brickId>032390f7-b7d1-4b64-8a50-ff2d838e8689</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="VARIABLE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>100</value>
                    </formula>
                  </formulaList>
                  <userVariable reference="../../../../../../../../scene[4]/objectList/object[4]/scriptList/script[6]/brickList/brick/loopBricks/brick/ifBranchBricks/brick/userVariable"/>
                </brick>
                <brick type="ShowTextBrick">
                  <brickId>fe8ba6e9-ebcb-4ce7-8256-274109c9e228</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>400</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>571</value>
                    </formula>
                  </formulaList>
                  <userVariable reference="../../../../../../../../scene[4]/objectList/object[4]/scriptList/script[6]/brickList/brick/loopBricks/brick/ifBranchBricks/brick/userVariable"/>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>f505f981-da1c-4eb2-afdf-90ad6901e15b</scriptId>
            </script>
            <script type="WhenConditionScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="BroadcastBrick">
                  <brickId>20f742ce-64d9-48b8-aecd-d3b93ee2aeb8</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Morte vegeta</broadcastMessage>
                </brick>
                <brick type="BroadcastBrick">
                  <brickId>8726bd2b-c920-4a85-95a9-6c6ecef1f5da</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Sumir goku</broadcastMessage>
                </brick>
                <brick type="WaitBrick">
                  <brickId>8e2f9df0-70b7-4758-9de0-abb0dab55e2b</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>3</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SceneStartBrick">
                  <brickId>afe522b2-7854-49c7-be84-0954ea6de9e3</brickId>
                  <commentedOut>false</commentedOut>
                  <sceneToStart>Game over</sceneToStart>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>19159b42-7460-4185-8ba3-6a09033e76be</scriptId>
              <formulaMap>
                <formula category="IF_CONDITION">
                  <additionalChildren/>
                  <leftChild>
                    <additionalChildren/>
                    <type>USER_VARIABLE</type>
                    <value>Vida_bot</value>
                  </leftChild>
                  <rightChild>
                    <additionalChildren/>
                    <rightChild>
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>1</value>
                    </rightChild>
                    <type>OPERATOR</type>
                    <value>MINUS</value>
                  </rightChild>
                  <type>OPERATOR</type>
                  <value>SMALLER_THAN</value>
                </formula>
              </formulaMap>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Imagem da vida goku">
          <lookList>
            <look fileName="goku_black___ulsw_sprite_sheet_by_songoku0911_ddebcai_#24.png" name="goku_black___ulsw_sprite_sheet_by_songoku0911_ddebcai">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>e1c4269d-d643-4532-b3fa-2986a5ab176f</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>1071</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>449</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>7c29e69f-e883-47ed-9225-2edc3867c3ad</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>250</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>3883e4b8-4220-4b23-981e-44876142fd2f</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Botão Ki">
          <lookList>
            <look fileName="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d_#2.png" name="Botão Ki">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d_#3.png" name="Botão Ki (1)">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>7d999c4e-d2a6-4b11-b102-6b9ed431a47b</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>900</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>464</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>9684c354-097d-457b-bfdb-a778f1e6a2d5</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>600</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>ee978cd4-f62a-436c-878f-c056ad57ca22</scriptId>
            </script>
            <script type="WhenScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="BroadcastBrick">
                  <brickId>236fba4b-729a-485d-8709-0ee1d931ca6f</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Kibast</broadcastMessage>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>7ed764eb-f8a7-4ad2-abb2-7c3f887629bc</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>500</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="WaitBrick">
                  <brickId>8704fb4b-4add-405f-8fdc-5b6d74e0459b</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.2</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>48e0b66e-6b54-4863-837a-c64edcd3ec37</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>600</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="HideBrick">
                  <brickId>571e552b-8bf8-4449-87aa-96bd77381dac</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
                <brick type="WaitBrick">
                  <brickId>511c73cb-2139-434e-bb6c-fa403e9b57d6</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>3</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="ShowBrick">
                  <brickId>762d9dc1-ee90-42dc-ac02-f69dfbe4136e</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>5d26597a-2f8c-4553-88fe-3950a077f3ca</scriptId>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="HideBrick">
                  <brickId>845f6165-7408-47c8-8da7-da0f9fd78920</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>a91c252b-10da-4c0a-b636-820b1b1f964d</scriptId>
              <receivedMessage>Mortegoku</receivedMessage>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Hitsoco">
          <lookList>
            <look fileName="Meu ator ou objeto.png" name="Hitsoco">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetTransparencyBrick">
                  <brickId>c0604fff-e99b-4021-8602-6f9b8a0b3134</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TRANSPARENCY">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>80</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="HideBrick">
                  <brickId>e39891ad-bd32-40e3-a6ff-b664accc3fea</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>5d8a13d7-48f4-46a9-8436-4037ed033b62</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>500</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="ForeverBrick">
                  <brickId>ee953fca-1bf5-4fc9-aaf8-be73594348d5</brickId>
                  <commentedOut>false</commentedOut>
                  <loopBricks>
                    <brick type="GoToBrick">
                      <brickId>348c21e7-1d92-4c83-930a-aea7a9c08202</brickId>
                      <commentedOut>false</commentedOut>
                      <destinationSprite reference="../../../../../../../../object[4]"/>
                      <spinnerSelection>82</spinnerSelection>
                    </brick>
                  </loopBricks>
                </brick>
                <brick type="SetXBrick">
                  <brickId>6a42486c-cd8d-4c44-bb9a-86d888412cd1</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>82</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>5a231495-0513-4378-b627-f19bc343e6e2</scriptId>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ShowBrick">
                  <brickId>cd615ad8-1fbb-46ae-87a6-c4e3558d95c3</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
                <brick type="WaitBrick">
                  <brickId>cb635237-5a71-4bda-ac32-6cbfe885486d</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.2</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="HideBrick">
                  <brickId>512ddfca-a35f-45da-b707-e513468be171</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>af8e7dad-9127-4e80-a95f-dca7a43ac262</scriptId>
              <receivedMessage>Soco</receivedMessage>
            </script>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ForeverBrick">
                  <brickId>1e256a8d-de05-42c3-aa9e-301dfe01d435</brickId>
                  <commentedOut>false</commentedOut>
                  <loopBricks>
                    <brick type="IfThenLogicBeginBrick">
                      <brickId>8c3e2056-4cfa-4642-a4be-99132bd754fe</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="IF_CONDITION">
                          <additionalChildren/>
                          <leftChild>
                            <additionalChildren/>
                            <type>COLLISION_FORMULA</type>
                            <value>Vegeta</value>
                          </leftChild>
                          <rightChild>
                            <additionalChildren/>
                            <type>FUNCTION</type>
                            <value>TRUE</value>
                          </rightChild>
                          <type>OPERATOR</type>
                          <value>EQUAL</value>
                        </formula>
                      </formulaList>
                      <ifBranchBricks>
                        <brick type="SetLookBrick">
                          <brickId>cb90de4d-4065-49df-a092-02952212b7fd</brickId>
                          <commentedOut>false</commentedOut>
                          <look reference="../../../../../../../../../lookList/look"/>
                        </brick>
                        <brick type="ChangeVariableBrick">
                          <brickId>9226f22c-0981-4aa3-bcd3-7c93f7d1493e</brickId>
                          <commentedOut>false</commentedOut>
                          <formulaList>
                            <formula category="VARIABLE_CHANGE">
                              <additionalChildren/>
                              <rightChild>
                                <additionalChildren/>
                                <type>NUMBER</type>
                                <value>1</value>
                              </rightChild>
                              <type>OPERATOR</type>
                              <value>MINUS</value>
                            </formula>
                          </formulaList>
                          <userVariable reference="../../../../../../../../../../../../scene[4]/objectList/object[4]/scriptList/script[6]/brickList/brick/loopBricks/brick/ifBranchBricks/brick/userVariable"/>
                        </brick>
                        <brick type="WaitBrick">
                          <brickId>5d2c8e68-073e-4286-80d4-1e116207a769</brickId>
                          <commentedOut>false</commentedOut>
                          <formulaList>
                            <formula category="TIME_TO_WAIT_IN_SECONDS">
                              <additionalChildren/>
                              <type>NUMBER</type>
                              <value>0.2</value>
                            </formula>
                          </formulaList>
                        </brick>
                        <brick type="SetLookBrick">
                          <brickId>cc0b1401-2e01-4631-8b77-9b9f2a3c69e4</brickId>
                          <commentedOut>false</commentedOut>
                          <look reference="../../../../../../../../../lookList/look"/>
                        </brick>
                        <brick type="ChangeVariableBrick">
                          <brickId>007a6fbd-96c0-4ef5-bbaf-a1176ca02dfa</brickId>
                          <commentedOut>false</commentedOut>
                          <formulaList>
                            <formula category="VARIABLE_CHANGE">
                              <additionalChildren/>
                              <rightChild>
                                <additionalChildren/>
                                <type>NUMBER</type>
                                <value>1</value>
                              </rightChild>
                              <type>OPERATOR</type>
                              <value>MINUS</value>
                            </formula>
                          </formulaList>
                          <userVariable reference="../../../../../../../../../../../../scene[4]/objectList/object[4]/scriptList/script[6]/brickList/brick/loopBricks/brick/ifBranchBricks/brick/userVariable"/>
                        </brick>
                        <brick type="WaitBrick">
                          <brickId>b09b831e-b72e-412b-8e36-4397ae573f19</brickId>
                          <commentedOut>false</commentedOut>
                          <formulaList>
                            <formula category="TIME_TO_WAIT_IN_SECONDS">
                              <additionalChildren/>
                              <type>NUMBER</type>
                              <value>0.2</value>
                            </formula>
                          </formulaList>
                        </brick>
                        <brick type="SetLookBrick">
                          <brickId>5b537d27-c4a1-4232-9a2e-4b86e38b6a7f</brickId>
                          <commentedOut>false</commentedOut>
                          <look reference="../../../../../../../../../lookList/look"/>
                        </brick>
                        <brick type="ChangeVariableBrick">
                          <brickId>0de93881-2c8b-4ee5-84dc-e426364a5018</brickId>
                          <commentedOut>false</commentedOut>
                          <formulaList>
                            <formula category="VARIABLE_CHANGE">
                              <additionalChildren/>
                              <rightChild>
                                <additionalChildren/>
                                <type>NUMBER</type>
                                <value>1</value>
                              </rightChild>
                              <type>OPERATOR</type>
                              <value>MINUS</value>
                            </formula>
                          </formulaList>
                          <userVariable reference="../../../../../../../../../../../../scene[4]/objectList/object[4]/scriptList/script[6]/brickList/brick/loopBricks/brick/ifBranchBricks/brick/userVariable"/>
                        </brick>
                        <brick type="WaitBrick">
                          <brickId>cdb6796c-648e-4430-a1ea-758ad2f0ec33</brickId>
                          <commentedOut>false</commentedOut>
                          <formulaList>
                            <formula category="TIME_TO_WAIT_IN_SECONDS">
                              <additionalChildren/>
                              <type>NUMBER</type>
                              <value>0.2</value>
                            </formula>
                          </formulaList>
                        </brick>
                        <brick type="SetLookBrick">
                          <brickId>45b35fd2-9b99-4c98-958f-76f8d381b9d5</brickId>
                          <commentedOut>false</commentedOut>
                          <look reference="../../../../../../../../../lookList/look"/>
                        </brick>
                      </ifBranchBricks>
                    </brick>
                  </loopBricks>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>ac6d23b4-84c5-4955-aeb0-52540c7716e3</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Kiblast">
          <lookList>
            <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#6.png" name="Kiblast">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#7.png" name="Kiblast (1)">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#8.png" name="Kiblast (2)">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_base_2_0_swl_repost_by_pablothespriter_dg7hrqd_#9.png" name="Kiblast (3)">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>b034c827-31a6-4b54-b398-c647227b99fc</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>134</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>640</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>a6d45e21-9112-4f5a-b32d-030dacd848af</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>300</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="HideBrick">
                  <brickId>d556632d-22cb-4fad-8775-783408bbe4bd</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>8b17d4ff-a483-412b-850b-f17645266a1e</scriptId>
            </script>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ForeverBrick">
                  <brickId>e2a1f764-9e31-401d-a3e7-0adedbbc9e4a</brickId>
                  <commentedOut>false</commentedOut>
                  <loopBricks>
                    <brick type="IfThenLogicBeginBrick">
                      <brickId>b31a512b-d705-45c1-acfd-1921598995df</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="IF_CONDITION">
                          <additionalChildren/>
                          <leftChild>
                            <additionalChildren/>
                            <type>COLLISION_FORMULA</type>
                            <value>Vegeta</value>
                          </leftChild>
                          <rightChild>
                            <additionalChildren/>
                            <type>FUNCTION</type>
                            <value>TRUE</value>
                          </rightChild>
                          <type>OPERATOR</type>
                          <value>EQUAL</value>
                        </formula>
                      </formulaList>
                      <ifBranchBricks>
                        <brick type="ChangeVariableBrick">
                          <brickId>563b7fbe-b27e-4bf5-9cc8-bb65c76e365c</brickId>
                          <commentedOut>false</commentedOut>
                          <formulaList>
                            <formula category="VARIABLE_CHANGE">
                              <additionalChildren/>
                              <rightChild>
                                <additionalChildren/>
                                <type>NUMBER</type>
                                <value>5</value>
                              </rightChild>
                              <type>OPERATOR</type>
                              <value>MINUS</value>
                            </formula>
                          </formulaList>
                          <userVariable reference="../../../../../../../../../../../../scene[4]/objectList/object[4]/scriptList/script[6]/brickList/brick/loopBricks/brick/ifBranchBricks/brick/userVariable"/>
                        </brick>
                        <brick type="ShowBrick">
                          <brickId>a924ca8a-3932-402a-b373-5639232d01be</brickId>
                          <commentedOut>true</commentedOut>
                        </brick>
                        <brick type="HideBrick">
                          <brickId>9a972270-9a6c-4870-aee1-06e66955fb2a</brickId>
                          <commentedOut>false</commentedOut>
                        </brick>
                      </ifBranchBricks>
                    </brick>
                  </loopBricks>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>4637d34b-3277-4f26-a061-0e5eb04b3eba</scriptId>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SetLookBrick">
                  <brickId>0b476c49-51e5-4f26-ab99-29dbe833a136</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look"/>
                </brick>
                <brick type="WaitBrick">
                  <brickId>9fd70cc3-ff37-4c7a-9b10-6b946e3d8ee0</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.1</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>b422c95a-95e8-4e0d-8c3e-4fa67cba38a4</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[2]"/>
                </brick>
                <brick type="WaitBrick">
                  <brickId>aeccfd3e-43da-425a-b54f-621d32a1c210</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.02</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>7f9002c6-8be4-4093-b92a-18207765cd64</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[3]"/>
                </brick>
                <brick type="WaitBrick">
                  <brickId>0a54eb21-9237-46b0-806d-fc757db6976b</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.02</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetLookBrick">
                  <brickId>43ca286e-5ce7-47bc-a4aa-858462dbe0e6</brickId>
                  <commentedOut>false</commentedOut>
                  <look reference="../../../../../lookList/look[4]"/>
                </brick>
                <brick type="ShowBrick">
                  <brickId>ae0ecc7b-3151-4146-914e-5ef4793e90f5</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
                <brick type="GoToBrick">
                  <brickId>680d42d2-f348-47b7-9832-f1819948c6da</brickId>
                  <commentedOut>false</commentedOut>
                  <destinationSprite reference="../../../../../../object[4]"/>
                  <spinnerSelection>82</spinnerSelection>
                </brick>
                <brick type="PointToBrick">
                  <brickId>0664620d-88b0-4b24-962a-9ca8dd3d604b</brickId>
                  <commentedOut>false</commentedOut>
                  <pointedObject reference="../../../../../../object[4]/scriptList/script/brickList/brick[4]/loopBricks/brick/pointedObject"/>
                </brick>
                <brick type="RepeatBrick">
                  <brickId>0f1b33b3-f7f4-4b2c-a0b6-6d9213baeff7</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIMES_TO_REPEAT">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>90</value>
                    </formula>
                  </formulaList>
                  <loopBricks>
                    <brick type="MoveNStepsBrick">
                      <brickId>f898e66f-6898-47c2-8adb-64ba27dfa8ac</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="STEPS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>20</value>
                        </formula>
                      </formulaList>
                    </brick>
                  </loopBricks>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>2f800c46-b4fe-46f1-a2c2-4f3dca6580f3</scriptId>
              <receivedMessage>Kibast</receivedMessage>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Botão Gamehameha">
          <lookList>
            <look fileName="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d_#4.png" name="Gamehameha">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>c078563d-c7ab-4fbd-8ec6-339e20c3428e</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>719</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>465</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>040be197-d198-4ff1-b7d8-46980fd8d674</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>600</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>61d8c1c3-526d-400a-9375-5c7ae0ba5814</scriptId>
            </script>
            <script type="WhenScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="BroadcastBrick">
                  <brickId>2b6def5f-facd-49dc-a9b1-922630fccbcb</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Gamehameha</broadcastMessage>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>15a14c10-94c5-413d-8f0a-2952abdbf0e7</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>500</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="WaitBrick">
                  <brickId>ea490d99-ac84-4955-bc1c-f3e8a5cbe3c9</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.2</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>787aea82-79d3-499c-a89e-7bc0f99b549f</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>600</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="HideBrick">
                  <brickId>b8f25dff-6b3e-4e73-bd31-b406594ea0fa</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
                <brick type="WaitBrick">
                  <brickId>1054891f-4154-418a-a037-cce699e3e347</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>5</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="ShowBrick">
                  <brickId>f8a92b48-08eb-4274-a19d-09fb4f204711</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>be7f18cc-aa5d-4fe8-84d5-7a67c7e4dcd4</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Gamehameha">
          <lookList>
            <look fileName="goku_black___ulsw_sprite_sheet_by_songoku0911_ddebcai_#12.png" name="1">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_black___ulsw_sprite_sheet_by_songoku0911_ddebcai_#14.png" name="2">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
            <look fileName="goku_black___ulsw_sprite_sheet_by_songoku0911_ddebcai_#15.png" name="3">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ForeverBrick">
                  <brickId>2adfacfa-97d6-4554-a955-2391a444be95</brickId>
                  <commentedOut>false</commentedOut>
                  <loopBricks>
                    <brick type="IfThenLogicBeginBrick">
                      <brickId>94944b5f-df40-45b9-a50a-03cf6965124c</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="IF_CONDITION">
                          <additionalChildren/>
                          <leftChild>
                            <additionalChildren/>
                            <type>COLLISION_FORMULA</type>
                            <value>Vegeta</value>
                          </leftChild>
                          <rightChild>
                            <additionalChildren/>
                            <type>FUNCTION</type>
                            <value>TRUE</value>
                          </rightChild>
                          <type>OPERATOR</type>
                          <value>EQUAL</value>
                        </formula>
                      </formulaList>
                      <ifBranchBricks>
                        <brick type="BroadcastBrick">
                          <brickId>fc5abda8-a88e-4070-a45c-d309006b2dc9</brickId>
                          <commentedOut>false</commentedOut>
                          <broadcastMessage>Acerto vegeta</broadcastMessage>
                        </brick>
                        <brick type="ChangeVariableBrick">
                          <brickId>5c7c4373-b42f-415a-b1dd-470b61ab71a1</brickId>
                          <commentedOut>false</commentedOut>
                          <formulaList>
                            <formula category="VARIABLE_CHANGE">
                              <additionalChildren/>
                              <rightChild>
                                <additionalChildren/>
                                <type>NUMBER</type>
                                <value>10</value>
                              </rightChild>
                              <type>OPERATOR</type>
                              <value>MINUS</value>
                            </formula>
                          </formulaList>
                          <userVariable reference="../../../../../../../../../../../../scene[4]/objectList/object[4]/scriptList/script[6]/brickList/brick/loopBricks/brick/ifBranchBricks/brick/userVariable"/>
                        </brick>
                        <brick type="ShowBrick">
                          <brickId>c79ee89e-830c-4546-a79e-cf3c6fd44467</brickId>
                          <commentedOut>true</commentedOut>
                        </brick>
                        <brick type="HideBrick">
                          <brickId>a1568ad9-edd2-4528-853d-c9bac6aa5e02</brickId>
                          <commentedOut>false</commentedOut>
                        </brick>
                      </ifBranchBricks>
                    </brick>
                  </loopBricks>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>6fd3b1b3-33db-4f00-98cd-c160259e6965</scriptId>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ShowBrick">
                  <brickId>a490b5d3-f3d9-43f4-8056-9d8fa685e388</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
                <brick type="GoToBrick">
                  <brickId>ead1684c-0e52-443a-81d8-bafda0771164</brickId>
                  <commentedOut>false</commentedOut>
                  <destinationSprite reference="../../../../../../object[4]"/>
                  <spinnerSelection>82</spinnerSelection>
                </brick>
                <brick type="PointToBrick">
                  <brickId>52fc73ff-a1ac-44d1-aba4-a0c3e2456d96</brickId>
                  <commentedOut>false</commentedOut>
                  <pointedObject reference="../../../../../../object[4]/scriptList/script/brickList/brick[4]/loopBricks/brick/pointedObject"/>
                </brick>
                <brick type="RepeatBrick">
                  <brickId>f907f278-c622-4fcd-8220-e8ac8e900012</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIMES_TO_REPEAT">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>90</value>
                    </formula>
                  </formulaList>
                  <loopBricks>
                    <brick type="MoveNStepsBrick">
                      <brickId>4da142c2-3843-4b3e-8bdb-70c9893700e7</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="STEPS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>250</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetSizeToBrick">
                      <brickId>db35e1c6-5f93-4552-b528-fc07caed0db7</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="SIZE">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>450</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetLookBrick">
                      <brickId>2307e5fc-c1ca-4387-b7da-08129c893f16</brickId>
                      <commentedOut>false</commentedOut>
                      <look reference="../../../../../../../lookList/look"/>
                    </brick>
                    <brick type="WaitBrick">
                      <brickId>513d8daa-e0f3-4928-bfe7-085038bdc815</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="TIME_TO_WAIT_IN_SECONDS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>0.1</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetSizeToBrick">
                      <brickId>e5e9744f-08d1-473c-b4d7-c39f33c52298</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="SIZE">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>500</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetLookBrick">
                      <brickId>7dafda69-96c5-4e9d-b595-b07e24abede1</brickId>
                      <commentedOut>false</commentedOut>
                      <look reference="../../../../../../../lookList/look[2]"/>
                    </brick>
                    <brick type="WaitBrick">
                      <brickId>0f690542-c8b9-4219-a146-73d956147ba3</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="TIME_TO_WAIT_IN_SECONDS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>0.2</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetSizeToBrick">
                      <brickId>00b87e5c-0087-4279-b920-46f22e133578</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="SIZE">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>600</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetLookBrick">
                      <brickId>4f30414c-a535-48fd-8130-9269530c2abc</brickId>
                      <commentedOut>false</commentedOut>
                      <look reference="../../../../../../../lookList/look[3]"/>
                    </brick>
                  </loopBricks>
                </brick>
                <brick type="WaitBrick">
                  <brickId>02b17607-2f73-4dff-9163-34865b822ad9</brickId>
                  <commentedOut>true</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.3</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>a682f097-87c3-41aa-86a4-2d5e6ff2a3e6</brickId>
                  <commentedOut>true</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>500</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>7ca41251-b707-46e1-8fd7-fe099212d2c0</scriptId>
              <receivedMessage>Gamehameha</receivedMessage>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ShowBrick">
                  <brickId>b641deee-a751-4391-bd8e-d93a6bedd07b</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
                <brick type="GoToBrick">
                  <brickId>1b92c124-72ed-45e6-a653-58a3aa786366</brickId>
                  <commentedOut>false</commentedOut>
                  <destinationSprite reference="../../../../../../object[4]"/>
                  <spinnerSelection>82</spinnerSelection>
                </brick>
                <brick type="PointToBrick">
                  <brickId>69758b28-075d-4b18-bb79-b3e5bac14074</brickId>
                  <commentedOut>false</commentedOut>
                  <pointedObject reference="../../../../../../object[4]/scriptList/script/brickList/brick[4]/loopBricks/brick/pointedObject"/>
                </brick>
                <brick type="RepeatBrick">
                  <brickId>57f911a8-961e-440e-9cbf-fe9c3f512f2b</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIMES_TO_REPEAT">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>90</value>
                    </formula>
                  </formulaList>
                  <loopBricks>
                    <brick type="MoveNStepsBrick">
                      <brickId>a51f0206-55d0-4ba6-96fc-eedc1f8de47b</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="STEPS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>250</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetSizeToBrick">
                      <brickId>4c8f86b3-6fa8-423c-a4e5-8041b6b2f7de</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="SIZE">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>450</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetLookBrick">
                      <brickId>b1b430c1-e89a-4eba-972d-877e3d2086a6</brickId>
                      <commentedOut>false</commentedOut>
                      <look reference="../../../../../../../lookList/look"/>
                    </brick>
                    <brick type="WaitBrick">
                      <brickId>5109b29d-832c-4bc4-a513-ee196cf552e6</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="TIME_TO_WAIT_IN_SECONDS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>0.1</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetSizeToBrick">
                      <brickId>4abde5d5-18a5-4c32-bbb1-8182e690370e</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="SIZE">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>500</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetLookBrick">
                      <brickId>1fb123eb-dada-4798-bb23-c9905b6f5211</brickId>
                      <commentedOut>false</commentedOut>
                      <look reference="../../../../../../../lookList/look[2]"/>
                    </brick>
                    <brick type="WaitBrick">
                      <brickId>ffb7f1b7-acb2-4062-85fd-214a1a4f231b</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="TIME_TO_WAIT_IN_SECONDS">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>0.2</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetSizeToBrick">
                      <brickId>b1272f13-4ba4-448f-bc2e-5ba33d82d153</brickId>
                      <commentedOut>false</commentedOut>
                      <formulaList>
                        <formula category="SIZE">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>600</value>
                        </formula>
                      </formulaList>
                    </brick>
                    <brick type="SetLookBrick">
                      <brickId>0ac725fb-6dc2-4b04-9e7c-14ec5c97662b</brickId>
                      <commentedOut>false</commentedOut>
                      <look reference="../../../../../../../lookList/look[3]"/>
                    </brick>
                  </loopBricks>
                </brick>
                <brick type="WaitBrick">
                  <brickId>49d6a52f-d8f9-43d9-9ad2-1c5606e6f1de</brickId>
                  <commentedOut>true</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.3</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>b40dd06b-0fec-47a8-b589-ca50845b3569</brickId>
                  <commentedOut>true</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>500</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>251a8e5d-95a0-4cda-862d-10004c5e7c83</scriptId>
              <receivedMessage>Gamehameha</receivedMessage>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Hitbox vegeta">
          <lookList>
            <look fileName="Meu ator ou objeto_#0.png" name="Hitbox vegeta">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="HideBrick">
                  <brickId>8b84615a-13ec-4fab-9dd9-b7036c5c5437</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
                <brick type="ForeverBrick">
                  <brickId>511f7af1-2534-4eee-943f-7e9ead864d09</brickId>
                  <commentedOut>false</commentedOut>
                  <loopBricks>
                    <brick type="GoToBrick">
                      <brickId>7874fa29-3837-42a7-9f37-da1cdfd404a9</brickId>
                      <commentedOut>false</commentedOut>
                      <spinnerSelection>80</spinnerSelection>
                    </brick>
                  </loopBricks>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>f64bbc10-628a-4e88-90f8-d45f50f3f2c5</scriptId>
            </script>
            <script type="WhenConditionScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="BroadcastBrick">
                  <brickId>6d8386c9-46ba-462d-b794-b358f2bb2893</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Mortegoku</broadcastMessage>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>250b6915-5a3d-4914-8d00-25946889f1ce</scriptId>
              <formulaMap>
                <formula category="IF_CONDITION">
                  <additionalChildren/>
                  <leftChild>
                    <additionalChildren/>
                    <type>COLLISION_FORMULA</type>
                    <value>Goku</value>
                  </leftChild>
                  <rightChild>
                    <additionalChildren/>
                    <type>FUNCTION</type>
                    <value>TRUE</value>
                  </rightChild>
                  <type>OPERATOR</type>
                  <value>EQUAL</value>
                </formula>
              </formulaMap>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Barreira ">
          <lookList>
            <look fileName="Meu ator ou objeto_#1.png" name="Barreira ">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="HideBrick">
                  <brickId>5220f497-705e-4536-b7e7-3e7050173a94</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
                <brick type="PlaceAtBrick">
                  <brickId>070df79b-f9f9-4eaa-83a7-a31f760af144</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>1209</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>26</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>ed904179-1fe1-471e-835c-69733c4c5b00</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>1000</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>fd0a0a84-2b54-46f2-840f-b4274b5a29de</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Resetar">
          <lookList>
            <look fileName="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d_#5.png" name="Resetar">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>90be62c3-f7f4-4441-91fc-e89fcacfe262</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>500</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>bb256126-a183-4a36-a802-c47cafcb5be3</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>500</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>4d57f267-6079-45bd-a8d6-2eb16c499f9e</scriptId>
            </script>
            <script type="WhenScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="SceneStartBrick">
                  <brickId>3e24304a-6911-4c10-bd32-ccea752a02af</brickId>
                  <commentedOut>false</commentedOut>
                  <sceneToStart>Cutscene</sceneToStart>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>c301e725-a541-4d1e-be07-7d6e2baa8d32</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="KH">
          <lookList>
            <look fileName="goku_black___ulsw_sprite_sheet_by_songoku0911_ddebcai_#23.png" name="KH">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ForeverBrick">
                  <brickId>ee7d3110-11bd-4305-bd0d-c3647eb04ade</brickId>
                  <commentedOut>true</commentedOut>
                  <loopBricks>
                    <brick type="IfThenLogicBeginBrick">
                      <brickId>5c22a17f-2e1a-47de-bd36-9f8bb83b4841</brickId>
                      <commentedOut>true</commentedOut>
                      <formulaList>
                        <formula category="IF_CONDITION">
                          <additionalChildren/>
                          <leftChild>
                            <additionalChildren/>
                            <type>COLLISION_FORMULA</type>
                            <value>Vegeta</value>
                          </leftChild>
                          <rightChild>
                            <additionalChildren/>
                            <type>FUNCTION</type>
                            <value>TRUE</value>
                          </rightChild>
                          <type>OPERATOR</type>
                          <value>EQUAL</value>
                        </formula>
                      </formulaList>
                      <ifBranchBricks>
                        <brick type="ChangeVariableBrick">
                          <brickId>d29b2093-0041-489c-9454-a04d4667df0c</brickId>
                          <commentedOut>true</commentedOut>
                          <formulaList>
                            <formula category="VARIABLE_CHANGE">
                              <additionalChildren/>
                              <rightChild>
                                <additionalChildren/>
                                <type>NUMBER</type>
                                <value>11</value>
                              </rightChild>
                              <type>OPERATOR</type>
                              <value>MINUS</value>
                            </formula>
                          </formulaList>
                          <userVariable reference="../../../../../../../../../../../../scene[4]/objectList/object[4]/scriptList/script[6]/brickList/brick/loopBricks/brick/ifBranchBricks/brick/userVariable"/>
                        </brick>
                        <brick type="BroadcastBrick">
                          <brickId>a210b6f4-967c-4531-a556-a25a10e467d4</brickId>
                          <commentedOut>true</commentedOut>
                          <broadcastMessage>Acerto vegeta</broadcastMessage>
                        </brick>
                      </ifBranchBricks>
                    </brick>
                  </loopBricks>
                </brick>
              </brickList>
              <commentedOut>true</commentedOut>
              <scriptId>3b621488-b0f0-44e2-a96e-b2c489ff1bb7</scriptId>
            </script>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="HideBrick">
                  <brickId>0bcb4a69-13dd-4ae0-ba1c-b63bee30b4ea</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>b6e3139e-fab4-43d1-b184-65f4933cbdda</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>300</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>064fe105-ee95-4b8e-93ea-33a59c28c918</scriptId>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ForeverBrick">
                  <brickId>3e94d147-128e-4e9d-8559-c5c0900068cc</brickId>
                  <commentedOut>true</commentedOut>
                  <loopBricks>
                    <brick type="ShowBrick">
                      <brickId>ed29e85e-2a23-45c2-826f-fdf417da0e98</brickId>
                      <commentedOut>true</commentedOut>
                    </brick>
                    <brick type="RepeatBrick">
                      <brickId>504b16ee-2bd3-40e3-b6da-65bfeca4d92c</brickId>
                      <commentedOut>true</commentedOut>
                      <formulaList>
                        <formula category="TIMES_TO_REPEAT">
                          <additionalChildren/>
                          <type>NUMBER</type>
                          <value>1</value>
                        </formula>
                      </formulaList>
                      <loopBricks/>
                    </brick>
                    <brick type="GoToBrick">
                      <brickId>df76404e-0790-4f96-a851-a63473ae385f</brickId>
                      <commentedOut>true</commentedOut>
                      <destinationSprite reference="../../../../../../../../object[4]"/>
                      <spinnerSelection>82</spinnerSelection>
                    </brick>
                    <brick type="PointToBrick">
                      <brickId>1a004fc0-5dba-48c6-bdb5-6e036e0dc0cd</brickId>
                      <commentedOut>true</commentedOut>
                      <pointedObject reference="../../../../../../../../object[4]/scriptList/script/brickList/brick[4]/loopBricks/brick/pointedObject"/>
                    </brick>
                    <brick type="IfThenLogicBeginBrick">
                      <brickId>8b482464-03d2-449b-805d-7c6923d3b7b3</brickId>
                      <commentedOut>true</commentedOut>
                      <formulaList>
                        <formula category="IF_CONDITION">
                          <additionalChildren/>
                          <leftChild>
                            <additionalChildren/>
                            <type>COLLISION_FORMULA</type>
                            <value>Vegeta</value>
                          </leftChild>
                          <rightChild>
                            <additionalChildren/>
                            <type>FUNCTION</type>
                            <value>TRUE</value>
                          </rightChild>
                          <type>OPERATOR</type>
                          <value>EQUAL</value>
                        </formula>
                      </formulaList>
                      <ifBranchBricks>
                        <brick type="ChangeVariableBrick">
                          <brickId>cab02822-5525-4f0a-93ef-6224812092a4</brickId>
                          <commentedOut>true</commentedOut>
                          <formulaList>
                            <formula category="VARIABLE_CHANGE">
                              <additionalChildren/>
                              <rightChild>
                                <additionalChildren/>
                                <type>NUMBER</type>
                                <value>10</value>
                              </rightChild>
                              <type>OPERATOR</type>
                              <value>MINUS</value>
                            </formula>
                          </formulaList>
                          <userVariable reference="../../../../../../../../../../../../scene[4]/objectList/object[4]/scriptList/script[6]/brickList/brick/loopBricks/brick/ifBranchBricks/brick/userVariable"/>
                        </brick>
                        <brick type="HideBrick">
                          <brickId>b8bc8b5f-2d6e-41c4-921d-e7d64d8ec960</brickId>
                          <commentedOut>true</commentedOut>
                        </brick>
                      </ifBranchBricks>
                    </brick>
                  </loopBricks>
                </brick>
              </brickList>
              <commentedOut>true</commentedOut>
              <scriptId>ac18ecec-6e9d-4352-a3de-28e3800353d1</scriptId>
              <receivedMessage>KH</receivedMessage>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="KH Botão ">
          <lookList>
            <look fileName="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d_#7.png" name="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>6433411c-1c3e-4c86-abd1-9962ef8dbd21</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>537</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>462</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>6706b438-5214-4643-9313-bcb58afb5456</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>600</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>892452c1-c3fc-42f9-9bc9-a627091ad8ad</scriptId>
            </script>
            <script type="WhenScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="BroadcastBrick">
                  <brickId>d9d6ad47-da7d-4ff4-a32b-e946b0f542f5</brickId>
                  <commentedOut>true</commentedOut>
                  <broadcastMessage>KH</broadcastMessage>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>fb8b686e-8d37-49e7-8dc9-5c27a75e0d8e</brickId>
                  <commentedOut>true</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>500</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="WaitBrick">
                  <brickId>a0547499-0dfe-439d-8e6e-6fa08b634f79</brickId>
                  <commentedOut>true</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.2</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>b7815e0b-85f5-45f0-9591-db8fc5b4819e</brickId>
                  <commentedOut>true</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>600</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="HideBrick">
                  <brickId>5df0bac2-5ad2-41ed-89c0-7a0a4ec25087</brickId>
                  <commentedOut>true</commentedOut>
                </brick>
                <brick type="WaitBrick">
                  <brickId>481e10cb-4f8e-430b-8a19-1ff23aff8bd9</brickId>
                  <commentedOut>true</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>10</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="ShowBrick">
                  <brickId>72be829c-3fa6-468b-8dea-a7de5cfe6205</brickId>
                  <commentedOut>true</commentedOut>
                </brick>
              </brickList>
              <commentedOut>true</commentedOut>
              <scriptId>b7b86666-f522-4b97-a8da-dc6c6d53b02d</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Tp botõe">
          <lookList>
            <look fileName="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d_#6.png" name="Tp botõe">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>aea37437-2b47-4c6b-a668-6b2786f39772</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>384</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>468</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>2eb9d44c-47cc-4787-9e4a-adbcbbdf07e3</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>600</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>c1571e72-d659-45c8-9dec-1a0bfa4f7317</scriptId>
            </script>
            <script type="WhenScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="BroadcastBrick">
                  <brickId>53752435-60f8-475a-b1ce-504aa483657e</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Tp</broadcastMessage>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>864ba036-2258-4a32-bee8-745e30649d1e</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>500</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="WaitBrick">
                  <brickId>beb1b51b-225d-4ff1-861d-59a39a15831b</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.2</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>fcbc9c0f-7db6-4636-b070-056d2d6e5a78</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>600</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="HideBrick">
                  <brickId>b047806f-0dba-4f9f-b36b-bcf8d3b7cfe1</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
                <brick type="WaitBrick">
                  <brickId>c769d1fa-20c8-42f5-b130-07469fd9bba5</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>3</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="ShowBrick">
                  <brickId>91ba61ec-d810-4126-b889-ad5ac62abd38</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>8bd987f3-2ef3-4a74-b9b5-5391b616f0ef</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Tp botõe (1)">
          <lookList>
            <look fileName="dghwo77-301461a9-f3e1-461f-8aa8-031cb871270d_#8.png" name="Tp botõe">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>ca79c0a5-3d08-435d-b3a3-366ade949f85</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>221</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>466</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>6b5d49e8-a3a8-4536-a952-4b0f23cc886a</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>600</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>bc9cfeed-1a0f-482d-b546-fba5dfe78a30</scriptId>
            </script>
            <script type="WhenScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="BroadcastBrick">
                  <brickId>0dbbf962-5cf0-4d46-81f0-c1e9ed36c1af</brickId>
                  <commentedOut>false</commentedOut>
                  <broadcastMessage>Tp 2</broadcastMessage>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>6cf4f33b-4a68-4337-913a-0f23cc634ffd</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>500</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="WaitBrick">
                  <brickId>ee1547ff-5197-4251-aef4-d9c62666080b</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>0.2</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>7fe31db2-e714-41fe-954e-03be85f5eb3b</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>600</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="HideBrick">
                  <brickId>6acd4d7b-4d1d-4417-9bbc-1905eec1d5de</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
                <brick type="WaitBrick">
                  <brickId>4fd2799d-5517-4621-81b9-d04521a1d985</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="TIME_TO_WAIT_IN_SECONDS">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>3</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="ShowBrick">
                  <brickId>d918b0bf-bfb8-431b-b2f8-d4054929922e</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>d59a4ebe-32e3-472c-af21-9f204c623429</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Barreira  (1)">
          <lookList>
            <look fileName="Meu ator ou objeto_#2.png" name="Barreira ">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>d7567712-1aef-43cd-9848-d455dd2eeb4f</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>1725</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>53</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="SetSizeToBrick">
                  <brickId>72c5b996-1d8a-45b8-8eb5-9460acd80c9d</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="SIZE">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>10000</value>
                    </formula>
                  </formulaList>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>3d138acf-0883-41e6-8d45-45e212347b1a</scriptId>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
        <object type="Sprite" name="Proibir ">
          <lookList>
            <look fileName="Meu ator ou objeto_#3.png" name="Proibir ">
              <isWebRequest>false</isWebRequest>
              <valid>true</valid>
            </look>
          </lookList>
          <soundList/>
          <scriptList>
            <script type="StartScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="PlaceAtBrick">
                  <brickId>5b6c1fb6-673f-4ad8-8cc7-4e03d074fbe5</brickId>
                  <commentedOut>false</commentedOut>
                  <formulaList>
                    <formula category="X_POSITION">
                      <additionalChildren/>
                      <type>NUMBER</type>
                      <value>593</value>
                    </formula>
                    <formula category="Y_POSITION">
                      <additionalChildren/>
                      <rightChild>
                        <additionalChildren/>
                        <type>NUMBER</type>
                        <value>404</value>
                      </rightChild>
                      <type>OPERATOR</type>
                      <value>MINUS</value>
                    </formula>
                  </formulaList>
                </brick>
                <brick type="HideBrick">
                  <brickId>64a1db29-cb04-4775-90af-3eb81cc92da9</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>766485cc-b4a4-4e23-917e-c3523a0a8768</scriptId>
            </script>
            <script type="BroadcastScript" posX="0.0" posY="0.0">
              <brickList>
                <brick type="ShowBrick">
                  <brickId>71d23103-f149-47c1-9520-548637bbd839</brickId>
                  <commentedOut>false</commentedOut>
                </brick>
              </brickList>
              <commentedOut>false</commentedOut>
              <scriptId>14379028-d531-430d-99cf-eb24b3cb3753</scriptId>
              <receivedMessage>Sumirvegeta</receivedMessage>
            </script>
          </scriptList>
          <nfcTagList/>
          <userVariables/>
          <userLists/>
          <userDefinedBrickList/>
        </object>
      </objectList>
    </scene>
  </scenes>
  <programVariableList>
    <userVariable reference="../../scenes/scene[2]/objectList/object[2]/scriptList/script[2]/brickList/brick[2]/userVariable"/>
    <userVariable reference="../../scenes/scene[2]/objectList/object[2]/scriptList/script[2]/brickList/brick[3]/userVariable"/>
    <userVariable reference="../../scenes/scene[2]/objectList/object[3]/scriptList/script[2]/brickList/brick[2]/userVariable"/>
    <userVariable reference="../../scenes/scene[4]/objectList/object[4]/scriptList/script/brickList/brick[4]/loopBricks/brick/pointedObject/scriptList/script[4]/brickList/brick/loopBricks/brick/ifBranchBricks/brick[2]/userVariable"/>
    <userVariable reference="../../scenes/scene[4]/objectList/object[4]/scriptList/script[6]/brickList/brick/loopBricks/brick/ifBranchBricks/brick/userVariable"/>
    <userVariable reference="../../scenes/scene[2]/objectList/object[7]/scriptList/script[2]/brickList/brick[2]/userVariable"/>
    <userVariable reference="../../scenes/scene[3]/objectList/object[12]/scriptList/script[2]/brickList/brick/loopBricks/brick[21]/userVariable"/>
    <userVariable reference="../../scenes/scene[2]/objectList/object[4]/scriptList/script[4]/brickList/brick[2]/userVariable"/>
  </programVariableList>
  <programListOfLists/>
  <programMultiplayerVariableList/>
</program>
