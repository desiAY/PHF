<template>
  <CRow>
    <CCol>
      <h1>PROGRESS HARIAN FUNGSIONAL</h1>
      <CCard class="mb-4"> </CCard>
      <CCard class="mb-4">
        <CCardHeader> INFORMASI IDENTITAS PEGAWAI </CCardHeader>
        <CCardBody>
          <div class="bd-example">
            <dl class="row">
              <dt class="col-sm-3">Nama Pegawai</dt>
              <dd class="col-sm-9">
                <p>Budianto</p>
              </dd>

              <dt class="col-sm-3">NIP</dt>
              <dd class="col-sm-9">
                <p>0123456789</p>
              </dd>

              <dt class="col-sm-3">Unit Kerja</dt>
              <dd class="col-sm-9">
                <p>Sub Keuangan</p>
              </dd>

              <dt class="col-sm-3">Satuan Kerja</dt>
              <dd class="col-sm-9">
                <dl class="row">
                  <dd class="col-sm-8">
                    <p>
                      Pusat Teknologi Informasi dan Pangkalan Data UIN Ar-Raniry
                    </p>
                  </dd>
                </dl>
              </dd>
            </dl>
          </div>
        </CCardBody>
      </CCard>
      <CCard class="mb-4">
        <CCardHeader> DATA PEKERJAAN HARIAN </CCardHeader>
        <CCardBody>
          <CForm>
            <CFormInput
              type="nama"
              id="exampleFormControlInput1"
              label="Nama Pegawai"
              placeholder=""
              text="Must be 8-20 characters long."
              aria-describedby="exampleFormControlInputHelpInline"
            />
          </CForm>
          <CForm>
            <CFormInput
              type="nip"
              id="exampleFormControlInput1"
              label="NIP"
              placeholder=""
              aria-describedby="exampleFormControlInputHelpInline"
            />
          </CForm>
          <CForm>
            <CFormInput
              type="jabatan"
              id="exampleFormControlInput1"
              label="Jabatan"
              placeholder=""
              aria-describedby="exampleFormControlInputHelpInline"
            />
          </CForm>
          <CForm>
            <CFormInput
              type="unit kerja"
              id="exampleFormControlInput1"
              label="Unit kerja"
              placeholder=""
              aria-describedby="exampleFormControlInputHelpInline"
            />
          </CForm>
          <CForm>
            <CFormInput
              type="satuan kerja"
              id="exampleFormControlInput1"
              label="Satuan kerja"
              placeholder=""
              aria-describedby="exampleFormControlInputHelpInline"
            />
          </CForm>
          <CForm>
            <CButton color="dark">Submit</CButton>
          </CForm>
        </CCardBody>
      </CCard>
    </CCol>
  </CRow>
</template>

<script></script>
