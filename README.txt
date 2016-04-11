<batch-execution lookup="LicenseSession">
  <insert>
      <com.redhat.license.Age>
            <age>19</age>
      </com.redhat.license.Age>
  </insert>
  <fire-all-rules/>
  <query out-identifier="eligibility" name="get eligibility"/>
</batch-execution>
